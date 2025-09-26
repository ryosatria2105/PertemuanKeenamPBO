## CRUD Java dengan JFrame Form & JDialog
## 📌 Deskripsi

Project ini merupakan implementasi CRUD (Create, Read, Update, Delete) menggunakan Java Swing sebagai GUI dan JDBC untuk koneksi ke database PostgreSQL yang dirancang dengan pola pemisahan antara Form utama (JFrame) sebagai tampilan data dan navigasi, serta JDialog untuk menangani input, edit, dan konfirmasi penghapusan data.

## ⚙️ Fitur Utama

Create (Insert Data)
- Tombol Insert di Form utama akan membuka JDialog berisi form input data.
- Data yang diisi akan disimpan ke database dengan query INSERT.

Read (Menampilkan Data)
- Data dari tabel database ditampilkan di JTable pada Form utama.
- Menggunakan query SELECT, ResultSet, dan DefaultTableModel.

Update (Mengubah Data)
- Tombol Update membuka JDialog dengan field yang sudah terisi data lama.
- Setelah diedit, perubahan disimpan dengan query UPDATE.

Delete (Menghapus Data)
- Tombol Delete menampilkan JDialog konfirmasi.
- Jika disetujui, data akan dihapus dengan query DELETE.

## 📊 Hasil Uji Coba
- Saat tombol Insert ditekan → muncul dialog input → setelah disimpan, data baru masuk ke tabel dan database.
- Saat tombol Update ditekan tanpa memilih data → muncul pesan peringatan.
- Saat tombol Update ditekan dengan data terpilih → dialog tampil dengan data lama, setelah disimpan muncul pesan “Data berhasil diupdate!”.
- Saat tombol Delete ditekan tanpa memilih data → muncul pesan peringatan.
- Saat tombol Delete ditekan dengan data terpilih → dialog tampil, setelah konfirmasi Yes → data berhasil dihapus.

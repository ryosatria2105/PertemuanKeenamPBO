# 🖥️📚 TUGAS PBO – Pertemuan Keenam  

**Implementasi Modal Dialog pada Aplikasi CRUD Member Gym (Java Swing + JDBC + PostgreSQL)**  

---

## 📄 Studi Kasus  
Tugas ini guna untuk **memenuhi mata kuliah Pemrograman Berorientasi Objek (PBO)** dengan studi kasus **CRUD Data Member Gym**.  
Aplikasi ini mengelola data **Member Gym** dengan operasi dasar **CRUD** (Create, Read, Update, Delete).  
Data yang dikelola mencakup:  
- 🆔 ID Member  
- 👤 Nama  
- 🏋️‍♂️ Tipe Paket  
- 🎯 Umur  
- 🧑‍🏫 Coach  

Pada tahap sebelumnya (Pertemuan 5), aplikasi sudah dapat melakukan CRUD langsung dari form utama. Namun pada tahap ini, ditambahkan konsep **Modal Dialog** agar interaksi pengguna menjadi lebih aman, terstruktur, dan profesional.  

---

## 🎭 Peran Modal Dialog  
Modal dialog digunakan agar **setiap aksi penting** (insert, update, delete) tidak dilakukan sembarangan.  

- ➕ **Dialog Insert**  
  Membuka jendela kecil untuk input data baru, lalu menyimpannya ke database.  
- 🔄 **Dialog Update**  
  Menampilkan data yang dipilih, memberi kesempatan user mengubah isinya sebelum disimpan ulang.  
- ❌ **Dialog Delete (Modal)**  
  Sebelum data terhapus, sistem akan menampilkan dialog konfirmasi.  
  → User harus memilih **“Yakin”** atau **“Batal”**.  
- 🎯 **Keunggulan Modal Dialog**  
  - Mengunci interaksi dengan form utama sampai dialog selesai.  
  - Mengurangi risiko human error (misalnya salah klik tombol delete).  
  - Membuat aplikasi lebih ramah pengguna dan mirip software profesional.  

---

## 📊 Alur CRUD dengan Dialog  
1. User memilih aksi dari form utama (Insert / Update / Delete).  
2. Program membuka **Dialog Modal** sesuai aksi.  
3. User mengisi / mengubah / mengkonfirmasi data.  
4. Jika disetujui, data diproses ke database `member_gym`.  
5. JTable pada form utama otomatis diperbarui.  

---

## 🖼️ Tampilan Aplikasi  
- Form utama dengan tabel data member gym.
  <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/c4a37292-e137-403e-be0b-33d61fa2c75e" />

- Dialog Insert untuk tambah data.
  <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/9db33bab-95ed-4384-910e-a08bf64963ba" />

- Dialog Update untuk ubah data.
  <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/5ac66ae1-d5e8-4e85-aed0-6406fafb6a84" />

- Dialog Delete (Modal) untuk konfirmasi hapus data.
  <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/0db75344-a77c-4157-8892-699c5c0068de" />

 

---

## 👨‍💻 Author  
**Ryo Satriagung Hidayat**  
NIM: 09010624015  
Program Studi: Sistem Informasi  
Universitas Islam Negeri Sunan Ampel Surabaya – 2025  


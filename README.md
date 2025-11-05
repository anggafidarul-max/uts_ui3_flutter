# UTS Mobile Programming Flutter - UI 3 Halaman

Proyek ini dibuat untuk memenuhi tugas UTS mata kuliah *Desain Web / Mobile (Flutter)*.
Aplikasi terdiri dari 3 halaman utama:

#1. Halaman Login

* Teks judul: “Selamat Datang”
* Deskripsi singkat aplikasi
* Gambar/logo (dummy)
* TextField: email & password
* Tombol Login
* Icon di TextField (Icons.person & Icons.lock)

# 2. Halaman Dashboard

* AppBar dengan judul & ikon notifikasi
* Header sapaan pengguna (“Halo, Selamat Datang 👋”)
* Gambar/banner
* 3 menu utama dalam bentuk Grid:

  * Profil  → Navigasi ke halaman profil
  * Data  → Menampilkan pesan “Data belum tersedia”
  * Pengaturan  → Menampilkan pesan “Pengaturan belum tersedia”

# 3. Halaman Profil

* Foto/avatar
* Nama, NIM/ID, Email
* Info tambahan (misal: Prodi – Semester)
* Tombol kembali ke Dashboard

# Komponen yang digunakan

* Text
* Gambar (Image.asset)
* Icon
* Column dan Row
* Navigator

📂 Struktur Folder Utama


lib/
 ├── main.dart
 ├── login_page.dart
 ├── dashboard_page.dart
 └── profile_page.dart
assets/
 └── images/
      ├── avatar.png
      ├── banner.png
      └── logo.png


 Cara Menjalankan

1. Jalankan perintah:

   bash
   flutter pub get
   flutter run
   
2. Pilih device (misal Chrome atau Windows)
3. Aplikasi akan tampil dengan halaman Login terlebih dahulu

Screenshot Tampilan

* Login Page
* Dashboard Page
* Profil Page

(Sertakan 3 screenshot di sini)

---

Dibuat oleh:
Nama: Muhammad Angga Fidarul Mustakim
NPM: 24670064
Kelas: 3B

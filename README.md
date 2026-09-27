# 📚 Students Inputs - Web Management Data

Aplikasi web dinamis berbasis **PHP Native** dan **MySQL** yang digunakan untuk mengelola data inputan siswa serta mata pelajaran, dilengkapi dengan sistem autentikasi pengguna (Login & Register).

---

## 🚀 Fitur Utama

- 🔐 **Autentikasi Pengguna:** Sistem Login (`login.php`) dan Register (`register.php`).
- 📊 **Dashboard & Navigasi Utama:** Tampilan ringkas menu utama aplikasi (`dashboard.php`, `menu.php`).
- 📝 **Manajemen Mata Pelajaran (CRUD):**
  - Menampilkan daftar mapel (`tampil_mapel.php`).
  - Menambah mapel baru (`tambah_mapel.php`).
  - Mengubah data mapel (`edit_mapel.php`).
  - Menghapus data mapel (`proses_hapus_mapel.php`).
- 🗄️ **Database Integration:** File skema database siap import (`users.sql`).

---

## 🛠️ Teknologi yang Digunakan

- **Bahasa Pemrograman:** PHP Native, HTML, CSS
- **Database:** MySQL
- **Web Server:** Apache (via XAMPP / Laragon)

---

## ⚙️ Cara Menjalankan Project Secara Lokal

1. **Clone/Download Repository:**
   
```bash
   git clone [https://github.com/Thierrydimarftcode/Students_Inputs.git](https://github.com/Thierrydimarftcode/Students_Inputs.git)
   
Pindahkan Folder Project:
Pindahkan folder Students_Inputs ke dalam direktori server lokal kamu:

XAMPP: C:/xampp/htdocs/

Laragon: C:/laragon/www/

Import Database:

Buka phpMyAdmin (http://localhost/phpmyadmin).

Buat database baru (misal: db_students).

Import file users.sql yang ada di dalam repository ini.

Konfigurasi Koneksi Database:
Buka file koneksi.php dan sesuaikan konfigurasi database jika diperlukan:

PHP
   $host = "localhost";
   $user = "root";
   $pass = "";
   $db   = "db_students"; // sesuaikan dengan nama database kamu
   
Akses Aplikasi:
Buka browser dan jalankan URL berikut:

Plaintext
   http://localhost/Students_Inputs/login.php
   
👤 Author
Dikembangkan oleh Thierrydimar

Project Pemrograman Web Dinamis Sederhana (PPLG)

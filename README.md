# UjiOnline - Aplikasi Ujian Berbasis Web dengan Laravel

**UjiOnline** adalah aplikasi berbasis web CBT yang dikembangkan menggunakan framework PHP populer yaitu **Laravel**. Aplikasi ini dibuat sebagai studi kasus dari kursus pengembangan website, dengan fokus pada sistem **ujian online (Computer Based Test)** yang dapat membantu guru atau manajer dalam mengevaluasi kemampuan siswa atau karyawan secara efisien.

## 🎯 Tujuan Proyek

Aplikasi CBT Online dikembangkan untuk mempermudah proses evaluasi dan ujian secara digital, baik dalam lingkungan pendidikan maupun korporasi. Tujuan utama dari aplikasi ini adalah:
- Menyediakan platform ujian yang efisien, fleksibel, dan mudah diakses.
- Memfasilitasi guru, dosen, atau manajer untuk membuat dan mengelola soal serta jadwal ujian secara digital.
- Memberikan pengalaman ujian yang interaktif dan real-time untuk siswa atau karyawan.
- Mengurangi ketergantungan terhadap ujian berbasis kertas serta meminimalisir kecurangan.
- Menjadi fondasi awal untuk dikembangkan menjadi sistem CBT yang lebih kompleks dan dapat digunakan secara luas di masa depan.

## 🧩 Fitur Utama

- 🔐 **Role-Based Access Control (RBAC):**
  - **Teacher / Manager**: 
    - Membuat dan mengelola soal
    - Menjadwalkan ujian
    - Melihat hasil ujian
  - **Student / Karyawan**: 
    - Mengikuti ujian yang diberikan
    - Melihat hasil ujian pribadi

- 📝 **Manajemen Ujian dan Soal:**
  - Dukungan soal pilihan ganda dan esai
  - Evaluasi hasil otomatis

- ⚙️ **User Experience Terjaga:**
  - Akses ke fitur dibatasi sesuai peran pengguna
  - Tampilan antarmuka yang ramah pengguna

## ⚙️ Teknologi yang Digunakan

- **Laravel** (PHP Framework)
- **Blade Templating Engine**
- **MySQL** (Database)
- **Tailwind CSS** (untuk antarmuka)
- **Authentication dan Middleware Laravel**

## 🚀 Cara Instalasi

1. **Clone repository:**
   ```bash
   git clone https://github.com/habibie11/ujionline.git
   cd ujionline
   ```

2. **Install dependency Laravel:**
   ```bash
   composer install
   ```

3. **Salin file konfigurasi dan buat kunci aplikasi:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Atur koneksi database pada file `.env`, kemudian migrasi database:**
   ```bash
   php artisan migrate
   ```

5. **Jalankan server lokal Laravel:**
   ```bash
   php artisan serve
   ```

6. **Akses di browser:**
   ```
   http://localhost:8000
   ```

## 👨‍💻 Pengembang

Proyek ini dikembangkan oleh Habibie sebagai bagian dari proses belajar Laravel dan membangun aplikasi web yang scalable dan mudah dikembangkan bersama tim.

## 🤝 Kontribusi

Kontribusi sangat terbuka! Jika kamu memiliki ide, perbaikan bug, atau ingin menambahkan fitur baru:
1. Fork repository ini
2. Buat branch baru untuk fitur atau perbaikanmu
3. Ajukan pull request

## 📷 Screenshot

_Tambahkan screenshot antarmuka aplikasi di sini jika ada_

---

> Terima kasih telah melihat proyek ini. Silakan beri ⭐️ jika kamu suka dan ingin mendukung pengembangannya!

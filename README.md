# Web Nawasena Native

Website **Web Nawasena Native**  
Dikembangkan oleh **LTHLabs** sebagai proyek pembelajaran untuk membuat website menggunakan PHP, JavaScript, dan CSS.

---

## ✨ Fitur

- Halaman utama (index) dengan tampilan HTML + CSS  
- Manajemen tabel data melalui `Dtable.php` dan `table.php`  
- Form tambah data (`addtable.php`)  
- Sistem logout (`TBlogout.php`)  
- Menyimpan / menampilkan data web menggunakan `dataApp.php`  
- Responsif sederhana dengan CSS custom  
- Gambar statis disimpan di folder `img`

---

## 📁 Struktur Proyek

Web_Nawasena_Native/
│
├── Index.php
├── addtable.php
├── app.css
├── dataApp.php
├── Dtable.php
├── Log_up.css
├── package-lock.json
├── package.json
├── table.php
├── TBlogout.php
│
├── img/
│   ├── Hero.png
│   ├── Logo taman.png
│   ├── Logo_Nawasena.png
│   ├── Logo_nawasena_2.png
│   ├── Logo_nawasena_icon_.png
│   └── Logo_nawasena_icon_light.png
│
└── README.md

---

## 🚀 Cara Menjalankan (Setup)

1. Clone repo ini:

   ```bash
   git clone https://github.com/LTHLabs/Web_Nawasena_Native.git
   cd Web_Nawasena_Native
Jalankan web server lokal:
Karena menggunakan PHP, kamu bisa pakai:

XAMPP / WAMP / MAMP: letakkan folder repo di htdocs (atau www)

PHP built-in server (jika versi PHP-mu mendukung):

bash
Copy code
php -S localhost:8000
Akses aplikasi: buka browser → http://localhost:8000/Index.php (atau path sesuai setup kamu).

📦 Dependensi
PHP (versi minimal tergantung fitur PHP apa yang dipakai)

Web server lokal (XAMPP / WAMP / Apache) / PHP built-in

(Opsional) Node.js / npm — jika package.json digunakan untuk skrip JS front-end

🧪 Tes & Pengembangan
Untuk menambahkan data: buka addtable.php, isi form → submit → data akan diproses oleh dataApp.php.

Untuk melihat data: buka table.php atau Dtable.php.

Untuk style: modifikasi file CSS (app.css, Log_up.css) sesuai kebutuhan.

Untuk image: tambahkan gambar ke folder img/ dan referensikan di halaman web.

💡 Kontribusi
Terima kasih jika kamu tertarik berkontribusi!
Beberapa cara kontribusi:

Tambah fitur baru (misalnya autentikasi, validasi form, pagination)

Perbaiki tampilan CSS agar lebih responsif / modern

Refaktor kode PHP agar lebih modular

Tambahkan dokumentasi atau contoh deployment production

📄 Lisensi
Proyek ini dilisensikan dengan MIT License — lihat file LICENSE untuk detail lengkap.

👤 Penulis
Luthfi.PR — pembuat awal repo
LTHLabs — lab / komunitas pengembang

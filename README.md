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

/
├── Index.php # Halaman utama
├── Dtable.php # Menampilkan data dalam tabel (dengan detail)
├── table.php # Halaman tabel data
├── addtable.php # Form untuk menambah data
├── TBlogout.php # Untuk logout / keluar (jika ada sesi)
├── dataApp.php # Backend PHP untuk mengolah data aplikasi
├── app.css # Style global
├── Log_up.css # Style untuk form login / registrasi
├── img/ # Folder gambar statis
└── package.json # Dependensi JavaScript (jika ada penggunaan npm)

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

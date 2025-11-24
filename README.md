# Web Nawasena Native

Website **Web Nawasena Native** dikembangkan oleh **LTHLabs** sebagai proyek pembelajaran untuk membuat website menggunakan PHP, JavaScript, dan CSS.

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

```
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
```

---

## 🚀 Cara Menjalankan (Setup)

### 1. Clone Repository

```bash
git clone https://github.com/LTHLabs/Web_Nawasena_Native.git
cd Web_Nawasena_Native
```

### 2. Jalankan Web Server Lokal

Karena menggunakan PHP, Anda bisa menggunakan:

**Opsi A: XAMPP / WAMP / MAMP**
- Letakkan folder repo di `htdocs` (atau `www`)
- Akses melalui browser: `http://localhost/Web_Nawasena_Native/Index.php`

**Opsi B: PHP Built-in Server**
```bash
php -S localhost:8000
```
- Akses melalui browser: `http://localhost:8000/Index.php`

---

## 📦 Dependensi

- PHP (versi minimal tergantung fitur PHP yang digunakan)
- Web server lokal (XAMPP / WAMP / Apache) atau PHP built-in server
- (Opsional) Node.js / npm — jika `package.json` digunakan untuk skrip JS front-end

---

## 🧪 Tes & Pengembangan

- **Menambahkan data**: Buka `addtable.php`, isi form → submit → data akan diproses oleh `dataApp.php`
- **Melihat data**: Buka `table.php` atau `Dtable.php`
- **Modifikasi style**: Edit file CSS (`app.css`, `Log_up.css`) sesuai kebutuhan
- **Menambah gambar**: Tambahkan gambar ke folder `img/` dan referensikan di halaman web

---

## 💡 Kontribusi

Terima kasih jika Anda tertarik berkontribusi! Beberapa cara kontribusi:

- Tambah fitur baru (misalnya autentikasi, validasi form, pagination)
- Perbaiki tampilan CSS agar lebih responsif / modern
- Refaktor kode PHP agar lebih modular
- Tambahkan dokumentasi atau contoh deployment production

---

## 📄 Lisensi

Proyek ini dilisensikan dengan **MIT License** — lihat file `LICENSE` untuk detail lengkap.

---

## 👤 Penulis

- **Luthfi.PR** — Pembuat awal repo
- **LTHLabs** — Lab / komunitas pengembang

---

## 📞 Kontak & Link

- GitHub: [LTHLabs](https://github.com/LTHLabs)
- Repository: [Web_Nawasena_Native](https://github.com/LTHLabs/Web_Nawasena_Native)

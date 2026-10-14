
# Repositori Praktikum Pemrograman Web 2026
*Informasi Mahasiswa:*
- *Nama:* Siti Maulida Rahayu
- *NIM:* 2406005
- *Kelas/Prodi:* Teknik Informatika - ITG
- *Kode MK:* IFRWP5151
---
## Catatan Modul 1
- Instalasi & Verifikasi Tools (VS Code, Node.js, Laragon, Git).
- Uji coba Laragon MySQL berjalan pada Port 3306.
- Konfigurasi identitas Git global.
---
### Spesifikasi Perangkat
- Sistem Operasi yang digunakan : Windows 11 Pro 64-bit (10.0, Build 26200)
- Kapasitas RAM : 16384MB RAM
- Versi Node.js : v24.21.0
- Versi Git : v2.56.0.windows.1
- Processor : 12th Gen Intel(R) Core(TM) i7-12700F (20 CPUs). ∼2.1GHz

---
## Catatan Modul 2 - Struktur Konten dan Semantik Dokumen HTML
*Tujuan:* Memahami anatomi dokumen HTML dan penggunaan tag semantik untuk SEO & aksesibilitas.

- *Anatomi Dokumen:* `<!DOCTYPE html>`, `<head>` (metadata), `<body>` (konten visual).
- *Tag Semantik vs Non-Semantik:*
    - Non-Semantik: `<div>`, `<span>` (tidak bermakna)
    - Semantik: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>` - menjelaskan peran konten ke browser & screen reader.

*Praktik yang Dikerjakan:*
1. Membuat folder `modul-2` dan file `index.html` berisi struktur Portofolio Pengembang Web:
      - `<header>` dengan judul "Portofolio Pengembang Web" dan `<nav>` (Beranda, Hubungi Saya)
      - `<main>` dengan `<section id="tentang">` dan `<section id="proyek">`
      - 2 buah `<article>` untuk Proyek Unggulan: 1. Sistem Manajemen Inventori Database (HTML, CSS, JS, MySQL), 2. Aplikasi Kasir & Perhitungan Transaksi (JS ES6+)
      - `<aside>` Status Pekerjaan dan `<footer>`
2. Membuat file `kontak.html` berisi Formulir Kontak dengan:
      - Input `text` Nama Lengkap, `email` Alamat Email, `select` Layanan (Pembuatan Web, Pengembangan Aplikasi, Lain-lain), `textarea` Pesan, dan button `submit` & `reset`.
3. Melakukan commit: `git add .`, `git commit -m "Menyelesaikan modul 2"`, `git push origin main`
4. Tugas Terstruktur: Membuat branch baru `pertemuan-2` / `modul-2` dan push.

---
## Catatan Modul 3 - Styling dan Tata Letak Antarmuka dengan CSS
*Tujuan:* Mengatur tampilan visual, pewarnaan, tipografi, dan tata letak responsif dengan CSS3.

- *Anatomi CSS:* Selector (h1, .card, #project) + Property & Value (color: #0d6efd;)
- *Konsep Box Model:* Setiap elemen dianggap kotak yang terdiri dari:
    1.  Content, 2. Padding (ruang dalam), 3. Border (garis tepi), 4. Margin (ruang luar)

*Praktik yang Dikerjakan:*
1. Membuat folder `modul-3`, menyalin HTML dari modul-2, dan membuat file `style.css`.
2. Implementasi CSS Modern:
      - Reset `* { margin:0; padding:0; box-sizing: border-box; }`
      - Styling `body` font Arial, background #f5f5f5, `header` background white
      - Navigasi `nav ul { display: flex; gap: 20px; }` dengan hover `color: #0d6efd`
      - Layout `main` max-width 900px, `section` background white padding 25px
      - Form `input, select, textarea { width: 100%; padding: 9px; border: 1px solid #ccc; }`
      - Button styling dan `aside` dengan `border-left: 3px solid #0d6efd`
      - Menyembunyikan `<hr> { display: none; }`
3. Uji Tampilan Responsif:
      - Menggunakan Developer Tools (F12) -> Toggle Device Toolbar (Ctrl+Shift+M)
      - Media Query `@media (max-width: 700px) { nav ul { flex-direction: column; gap: 8px; } }`
4. Customisasi Pribadi (sesuai tugas): Mengganti accent color menjadi pink `#df9797 / #9b5353`, menengahkan header, dan mengatur jarak antar section.
5. Commit: `git commit -m "menyelesikan modul 3 styling dan layout modern css"` dan `git commit -m "menambahkan custom accent color dan hover effect pada modul 3"`

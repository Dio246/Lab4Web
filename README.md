# Praktikum Pemrograman Web - CSS Layouting

Repositori ini berisi hasil praktikum pembuatan layout website responsif dan sederhana menggunakan HTML5 dan CSS3. Berikut adalah penjelasan dari setiap tahapan praktikum yang dilakukan:

## Langkah 1: Memahami Konsep Box Element & Float
Pada tahap awal, kita mempelajari konsep tata letak (layouting) dasar menggunakan properti CSS `float`. 
- Dibuat tiga buah kotak (Div 1, Div 2, Div 3) yang diberikan properti `float: left` agar berjajar secara horizontal berdampingan.
- Ditambahkan kotak keempat (Div 4) di bawahnya dengan memberikan properti `clear: left` dan `float: none`. Hal ini berfungsi agar kotak keempat tidak ikut mengambang ke kiri dan memaksa posisinya turun ke baris baru.

## Langkah 2: Reset CSS dan Pembuatan Struktur Dasar (Header)
Untuk memastikan tampilan konsisten di semua browser, dilakukan "Reset CSS" sederhana dengan menghapus margin dan padding bawaan (`margin: 0; padding: 0;`).
- Font diatur menggunakan Google Fonts (`Open Sans`).
- Seluruh konten dibungkus dalam sebuah id `#container` yang memiliki lebar statis (`980px`), diposisikan di tengah (`margin: 0 auto`), dan diberi efek bayangan (`box-shadow`).
- Bagian `<header>` dibuat dengan teks judul yang diberi margin dan warna abu-abu gelap agar terlihat elegan.

## Langkah 3: Pembuatan Menu Navigasi (Navbar)
Menu navigasi diletakkan di bawah header menggunakan tag `<nav>`.
- Navbar diberikan latar belakang biru solid pekat.
- Tautan (link) di dalamnya diubah menjadi `display: inline-block` agar berjajar secara horizontal dan dapat diberikan *padding* agar lebih luas.
- Ditambahkan efek *hover* (perubahan warna biru menjadi lebih gelap saat kursor diarahkan ke menu) dan kelas `.active` untuk penanda halaman yang sedang dibuka.

## Langkah 4: Pembuatan Hero Section (Jumbotron) & Layout Utama
Halaman dilengkapi dengan bagian sapaan utama menggunakan tag `<section id="hero">`.
- Area ini menampilkan judul besar "Hello World!" beserta paragraf deskripsi singkat bergaya tipografi yang rapi.
- Pada tahap ini, tag pembungkus `<section id="wrapper">` juga mulai didefinisikan untuk memisahkan antara *Main Content* (konten utama) dan *Sidebar* (bilah sisi). Di bagian paling bawah halaman, ditambahkan `<footer>` berisi teks *copyright*.

## Langkah 5: Penambahan Sidebar (Bilah Sisi)
Pada bagian `<aside id="sidebar">`, ditambahkan beberapa komponen pelengkap (widget).
- **Widget Link:** Berisi daftar menu vertikal (menggunakan tag `<ul>` dan `<li>`) yang memiliki gaya seragam dengan tema website.
- **Widget Text:** Berisi paragraf teks informasi statis.
Sidebar ini dirancang untuk diletakkan di sebelah kiri atau kanan konten utama halaman.

## Langkah 6: Pembuatan Konten Utama (Grid Layout)
Di dalam `<section id="main">`, konten utama dibagi menjadi tiga kolom sejajar (grid) menggunakan kombinasi kelas `.row` dan `.box`.
- Setiap kotak (box) berisi gambar *placeholder* berbentuk lingkaran, judul (*heading*), deskripsi paragraf singkat, dan sebuah tombol bergaya khusus (`.btn-default`) dengan teks "View detail". Layout ini merupakan dasar dari pembuatan bentuk *card* konten.

## Langkah 7: Styling Artikel dan Perataan Gambar
Untuk halaman artikel, didefinisikan kelas `.entry` dengan line-height yang lebih longgar agar teks mudah dibaca.
- Pada tahap ini dilatih cara meratakan gambar terhadap teks (*text wrapping*). Gambar diatur dengan properti `float: left` agar teks mengalir di sisi kanannya.
- Terdapat juga konfigurasi `.right-img` dengan `float: right` untuk memposisikan gambar di sebelah kanan teks, serta kelas `.divider` untuk memberikan garis pembatas horizontal antar seksi.

## Langkah 8: Pembuatan Halaman About & Portofolio
Sebuah halaman profil (`<article id="about">`) ditambahkan yang berisi perkenalan singkat.
- Di bawah teks perkenalan, dipasang daftar portofolio (seperti Web E-Commerce, Aplikasi Kasir, Company Profile) yang menggunakan teknik grid layout yang sama dengan langkah ke-6. Ini menunjukkan reusabilitas (penggunaan ulang) kode CSS pada bagian halaman yang berbeda.

## Langkah 9: Pembuatan Form Kontak
Tahap terakhir adalah merancang halaman interaktif menggunakan formulir kontak (`<article id="kontak">`).
- Menggunakan tag `<form>` dengan metode pengiriman `POST`.
- Dilengkapi dengan label dan input standar seperti *Nama Lengkap* (`type="text"`), *Email* (`type="email"`), *Subjek*, dan *Pesan* yang menggunakan `<textarea>`.
- Tombol kirim pesan (`<button type="submit">`) menggunakan kelas gaya tombol yang sama dengan yang ada di halaman utama agar tema tetap konsisten.
- <img width="1366" height="768" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/a8da27d6-1c7b-4973-91d1-123586c8a524" />
<img width="1366" height="768" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/d78be872-e724-4c7d-be07-962e639b4034" />
<img width="1366" height="768" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/cb6a890f-4503-43c0-a387-47e70a31d329" />
<img width="1366" height="768" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/7779906b-5b60-48a6-ab4b-42a95891477e" />
<img width="1366" height="768" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/c5bd2995-356b-4029-9be3-3203d1433974" />
<img width="1366" height="768" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/24b7472f-fe45-4344-9395-019135d8c2e5" />
<img width="1366" height="768" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/5bba0e76-ca79-44ef-b1c5-d7ea56b8b657" />
<img width="1366" height="768" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/19baab5f-06da-4184-bea6-df9c0cef930c" />
<img width="1366" height="768" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/aa1aabfb-da5a-41ff-bed1-45bbaee3bdac" />
<img width="1366" height="768" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/0f3272d7-1150-4950-9953-b897683b44c9" />
<img width="1366" height="768" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/73998aa7-bf8e-4089-a52b-28213e40b8e4" />
<img width="1366" height="768" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/ef3e4cbd-168a-4e35-b772-68833f1ce115" />
<img width="1366" height="768" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/17ba93f9-dad4-40b9-86c8-fcb24318f3f2" />

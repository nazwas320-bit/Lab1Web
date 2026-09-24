# README Praktikum 1 - HTML Dasar

## Identitas

**Nama:** Nazwa Salsabila  
**NIM:** 312510155  
**Program Studi:** Teknik Informatika  
**Mata Kuliah:** Pemrograman Web  
**Praktikum:** Praktikum 1 - HTML Dasar  

---

# Proses Praktikum

## 1. Persiapan Praktikum

Pada praktikum pertama, saya menggunakan Visual Studio Code sebagai text editor untuk membuat dan mengedit file HTML. Selain itu, web browser digunakan untuk melihat hasil dari kode HTML yang dibuat.

Pertama, saya membuat folder dengan nama:

praktikum-1-html-dasar
Kemudian membuat file: index.html

## 2. Membuat Struktur Dasar HTML
Langkah pertama adalah membuat struktur dasar dokumen HTML menggunakan HTML5.
Kode yang digunakan:
<!DOCTYPE html>
<html>
<head>
    <title>Praktikum HTML Dasar</title>
</head>
<body>
</body>
</html>

##3. Membuat Paragraf
Kode yang digunakan:
<!-- Ini adalah paragraf pertama -->
<p>
Kami sedang belajar HTML dasar pada mata kuliah Pemrograman Web.
Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
</p>

<!-- Ini adalah paragraf kedua -->
<p>
HTML digunakan untuk menyusun struktur dan konten halaman web.
Browser akan menampilkan hasil interpretasi dari dokumen HTML.
</p>

##4. Menambahkan Judul
Setelah membuat paragraf, saya menambahkan judul utama dan subjudul menggunakan tag <h1> dan <h2>.
Kode yang digunakan:
<!-- judul utama -->
<h1>Belajar Dasar HTML</h1>

<!-- subjudul -->
<h2>Paragraf pada HTML</h2>

##5. Memformat Teks
Pada tahap berikutnya, saya mencoba beberapa tag untuk memformat teks, seperti teks tebal, teks miring, teks penting, subscript, dan superscript.
Kode yang digunakan:
<p>
Kami sedang belajar <b>HTML dasar</b> pada mata kuliah
<i>Pemrograman Web</i>.
</p>

<p>
HTML merupakan <strong>bahasa markup</strong> untuk menyusun
struktur halaman web.
</p>

<p>
Air ditulis sebagai H<sub>2</sub>O dan luas dapat ditulis
sebagai x<sup>2</sup>.
</p>

##6. Menambahkan Gambar
Selanjutnya, saya menambahkan sebuah gambar ke dalam halaman HTML.
Sebelumnya dibuat folder:images/
Kemudian gambar disimpan di dalam folder tersebut dengan nama:profil mahasiswa.jpg

Struktur folder menjadi:
praktikum-1-html-dasar/
├── index.html
└── images/
    └── profil.jpg

Kode yang digunakan:
<h3>Menambahkan Gambar</h3>

<img src="images/profil.jpg"
     width="200"
     alt="Foto profil mahasiswa"
     title="Foto Profil Mahasiswa">

Kode yang digunakan:
<h3>Menambahkan Gambar</h3>

<img src="images/profil.jpg"
     width="200"
     alt="Foto profil mahasiswa"
     title="Foto Profil Mahasiswa">
##7. Mengatur Ukuran Gambar
Pada tahap ini, saya mencoba mengatur ukuran gambar menggunakan atribut width.
Kode:
<img src="images/profil.jpg"
     width="200"
     alt="Foto profil mahasiswa">

##8. Membuat Hyperlink
Selanjutnya, saya membuat file baru dengan nama:
halaman2.html
Kemudian membuat navigasi yang menghubungkan halaman utama, halaman kedua, dan website eksternal.
Kode:
<!-- navigasi halaman -->
<nav>
    <a href="index.html">Dasar HTML</a>
    <a href="halaman2.html">Halaman 2</a>
    <a href="https://www.google.com">Website Eksternal</a>
</nav>
<hr>

##9. Membuat List
Pada tahap ini, saya membuat daftar menggunakan unordered list dan ordered list.
Unordered List
<h2>Keahlian</h2>

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
Ordered List
<h2>Urutan Belajar</h2>

<ol>
    <li>Mempelajari struktur HTML</li>
    <li>Mempelajari tag dan atribut</li>
    <li>Membuat halaman HTML</li>
    <li>Menguji halaman pada browser</li>
</ol>

##10. Menambahkan Komentar
Selanjutnya, saya mencoba membuat komentar pada kode HTML.
Kode:
<!-- Bagian Profil Mahasiswa -->
<h2>Profil Mahasiswa</h2>

<!-- Bagian Keahlian -->
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>

##11. Menggabungkan Semua Elemen
Profil Mahasiswa

Data Diri
- Nama
- Program Studi
- Deskripsi

Keahlian
- HTML
- CSS
- JavaScript

Target Belajar
1. Menguasai HTML
2. Menguasai CSS
3. Menguasai JavaScript

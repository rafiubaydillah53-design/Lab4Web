 Laporan Praktikum 4 - CSS Layout

Nama: Rafi Ubaydillah

NIM: 312410542

Kelas: TI.24.A5

Mata Kuliah: Pemrograman Web

Dosen: Agung Nugroho, S.Kom., M.Kom.


🔹 Tujuan Praktikum

Memahami struktur dasar pembuatan layout web.

Memahami konsep box element.

Memahami penggunaan CSS Float Property.

Memahami HTML5 Semantic Element.

Membuat layout web sederhana.


⚙️ Langkah-Langkah Praktikum

1️⃣ Membuat File lab4_box.html

Membuat struktur HTML dasar dengan judul Box Element.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Box Element</title>
</head>
<body>
  <header>
    <h1>Box Element</h1>
  </header>
</body>
</html>

![Screenshot 1](Screenshot_1.png)
screenshot tampilan awal lab4_box.html di browser

2️⃣ Menambahkan Box Element

Menambahkan elemen <div> untuk membuat tiga box berwarna.

<section>
  <div class="div1">Div 1</div>
  <div class="div2">Div 2</div>
  <div class="div3">Div 3</div>
</section>

<style>
  div {
    float: left;
    padding: 10px;
  }
  .div1 { background: red; }
  .div2 { background: yellow; }
  .div3 { background: green; }
</style>

![Screenshot 11](Screenshot_11.png)
hasil tampilan tiga box sejajar horizontal

3️⃣ Menambahkan Clearfix

Menambahkan <div class="div4"> dengan property clear untuk mengatur posisi setelah float.

.div4 {
  background-color: blue;
  clear: left;
  float: none;
}

![Screenshot 3](Screenshot_3.png)
hasil setelah ditambahkan box keempat di bawah tiga box pertama

4️⃣ Membuat Layout Web Sederhana

Membuat folder baru lab4_layout, lalu membuat file home.html dan style.css.

Struktur HTML dasar:

<div id="container">
  <header><h1>Layout Sederhana</h1></header>
  <nav>
    <a href="home.html" class="active">Home</a>
    <a href="artikel.html">Artikel</a>
    <a href="about.html">About</a>
    <a href="kontak.html">Kontak</a>
  </nav>
  <section id="hero"></section>
  <section id="wrapper">
    <section id="main"></section>
    <aside id="sidebar"></aside>
  </section>
  <footer>
    <p>&copy; 2025 - Universitas Pelita Bangsa</p>
  </footer>
</div>

![Screenshot 4](Screenshot_4.png)
tampilan kerangka layout di browser

5️⃣ Menambahkan Navigasi, Hero Panel, dan Sidebar

Menambahkan warna dan efek hover pada navigasi.

Menambahkan bagian hero dengan teks dan tombol.

Membuat sidebar dengan widget link dan teks.

![Screenshot 5](Screenshot_5.png)
![Screenshot 6](Screenshot_6.png)
![Screenshot 7](Screenshot_7.png)
tampilan navigasi + hero panel + sidebar

6️⃣ Menambahkan Konten Utama (Main Content)

Menambahkan beberapa box konten dan artikel menggunakan <section> dan <article>.

![Screenshot 8](Screenshot_8.png)
hasil tampilan konten utama dan artikel di layout

7️⃣ Menambahkan Layout About

File: about.html

Berisi deskripsi diri dan portfolio.

![Screenshot 9](Screenshot_9.png)
tampilan halaman About

8️⃣ Menambahkan Layout Kontak

File: kontak.html

Berisi form input nama, email, dan pesan.

![Screenshot 10](Screenshot_10.png)
tampilan halaman form kontak

📄 Kesimpulan

Dalam praktikum ini saya mempelajari:

Konsep box element dan cara mengatur layout menggunakan CSS Float.

Penggunaan HTML5 semantic element seperti header, nav, section, article, footer.

Cara membuat layout web sederhana yang terstruktur dan responsif.

Cara menambahkan halaman tambahan seperti About dan Contact.

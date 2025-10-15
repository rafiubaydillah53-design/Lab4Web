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

![Screenshot 3](Screenshot_3.png)


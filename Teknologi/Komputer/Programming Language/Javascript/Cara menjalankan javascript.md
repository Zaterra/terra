---
file-created: 2022-12-27
page: 3
---
tags:: #programming #javascript 
links:: [[Javascript]]

Ada dua cara menjalan kan JavaScript

## Browser

 Ada tiga cara untuk menjalan JavaScript di browser

  ### Menggunakan file external

  Untuk menyertakan file JavaScript ke dalam file HTML, gunakan tag `<script>` dengan atribut `src` yang menunjukkan lokasi file JavaScript:
  ```html
  <script src="nama-file.js"></script>
```
  Tag `<script>` ini biasanya diletakkan di bagian akhir file HTML, agar tidak menghambat proses rendering halaman.
  
  ### Menjalankan langsung dalam satu file

  Selain menyertakan file JavaScript ke dalam file HTML, Anda juga dapat menuliskan kode JavaScript langsung ke dalam file HTML dengan menggunakan tag `<script>`. Kode JavaScript tersebut akan dijalankan oleh browser saat file HTML tersebut dibuka.

   Untuk menuliskan kode JavaScript ke dalam file HTML, gunakan tag `<script>` seperti ini:
   ```js
   <script>
  console.log("Hello, World!");
</script>

```

  ### Menggunakan dev-tool di browser
  
  Untuk menjalankan JavaScript di browser menggunakan dev tool, pertama-tama perlu membuka dev tool terlebih dahulu. Cara membukanya tergantung pada browser yang digunakan.
  Seperti contoh kits memakai **chrome**

  Di Google Chrome, tekan tombol F12 atau klik kanan pada halaman yang terbuka, lalu pilih "Inspect" dari menu yang muncul.

  Setelah dev tool terbuka, Anda dapat menjalankan kode JavaScript di dalamnya dengan menggunakan console. Caranya adalah sebagai berikut:
  
   1. Pilih tab "Console" di dev tool.
   2. Ketikkan kode JavaScript yang ingin Anda jalankan di kolom yang tersedia.
   3. Tekan enter untuk menjalankan kode tersebut.
Contoh: `> console.log("Hello, World!")`


## [[NodeJS]]

 Kita juga menjalankannya di [[NodeJS]]
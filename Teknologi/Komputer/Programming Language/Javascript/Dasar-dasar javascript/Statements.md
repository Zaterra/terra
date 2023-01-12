---
file-created: 2022-12-28
page: 3
---
tags:: #programming #javascript 
links:: [[Dasar-dasar javascript]]

**Contoh**
```js
let x, y, z;    // Statement 1
x = 5;          // Statement 2
y = 6;          // Statement 3
z = x + y;      // Statement 4
```

## Javascript Programs

Program komputer adalah daftar "instruksi" yang akan "dijalankan" oleh komputer.

Dalam bahasa pemrograman, instruksi pemrograman ini disebut Statement/Pernyataan.

Program JavaScript adalah daftar Statement/Pernyataan pemrograman.

## Javascript Statements

**Statement JavaScript terdiri dari:**
Nilai, Operator, Ekspresi, Kata Kunci, dan Komentar.

Kebanyakan program JavaScript berisi banyak Statement JavaScript.

Statement-Statement tersebut dijalankan satu per satu, sesuai dengan urutan penulisan mereka.

==Program JavaScript (dan Statement JavaScript) sering disebut sebagai kode JavaScript.==

## Semikolon ;

Tanda titik koma memisahkan Statement JavaScript.

Tambahkan tanda titik koma di akhir setiap pernyataan yang dapat dijalankan:

**Contoh**
```js
let a, b, c;  // Declare 3 variables
a = 5;        // Assign the value 5 to a
b = 6;        // Assign the value 6 to b
c = a + b;    // Assign the sum of a and b to c
```

 Ketika dipisahkan oleh tanda titik koma, beberapa pernyataan dalam satu baris diizinkan:
 ```js
let a = 5; let b = 6; let c = a + b;
```

Di JavaScript yang sekarang, tidak selalu diperlukan tanda titik koma untuk memisahkan pernyataan. Secara default, JavaScript akan menambahkan tanda titik koma secara otomatis di akhir pernyataan yang dianggap membutuhkannya. Ini disebut "tanda titik koma otomatis" atau =="ASI" (Automatic Semicolon Insertion).==
```js
let x, y, z
x = 5
y = 6
z = x + y
```
Namun, meskipun tidak wajib, ==sebaiknya tetap menggunakan tanda titik koma secara teratur dalam kode JavaScript Anda.== Hal ini akan membantu menghindari masalah yang mungkin timbul akibat ASI yang tidak sesuai harapan. Selain itu, menggunakan tanda titik koma secara teratur akan membuat kode Anda lebih mudah dibaca dan dipahami oleh orang lain yang mungkin akan bekerja dengan kode tersebut.

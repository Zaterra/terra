---
file-created: 2022-12-28
page: 6
---
tags:: #programming #javascript 
links:: [[Dasar-dasar javascript]]

## Operator matematika

| Operator | Description |
| -------- | ----------- |
| +        | Tambah      |
| -        | Kurang      |
| *        | Kali        |
| /        | Bagi        |
| %        | Modulus(Sisa bagi)     |
| ++       | Pertambahan |
| --         |     pengurangan        |

**Contoh**

```js
console.log(10+10); // 20
console.log("Hello "+"World"); // Hello World
console.log(10-5); // 15
console.log(10*2); // 20
console.log(10/2); // 5
console.log(6%2); // 0
var x = 0; x++; console.log(x); // 1
x--; console.log(x); // 0
```

## Assignment operators

Assignment operator adalah operator yang digunakan untuk menetapkan nilai ke dalam sebuah variabel.

| Operator | Description                                                  |
| -------- | ------------------------------------------------------------ |
| =        | Menetapkan nilai ke dalam sebuah variabel                    |
| +=       | Menambahkan nilai ke dalam sebuah variabel dan menetapkannya |
| -=       | Mengurangi nilai dari sebuah variabel dan menetapkannya      |
| *=       | Membagi nilai dari sebuah variabel dan menetapkannya         |
| /=       | Membagi nilai dari sebuah variabel dan menetapkannya         |
| %=       | Menghitung sisa bagi dari sebuah variabel dan menetapkannya  |
 
**Contoh penggunaan assignment operator:**

```js
var x = 10;
x += 5; // x sekarang bernilai 15
x -= 2; // x sekarang bernilai 13
x *= 3; // x sekarang bernilai 39
x /= 2; // x sekarang bernilai 19.5
x %= 3; // x sekarang bernilai 0.5
```


## Comparison Operators

| Operator | Description                       |
| -------- | --------------------------------- |
| ==       | Equal to                          |
| ===      | Equal value and equal type equal  |
| !=       | Not equal to                      |
| !==      | Not equal value or not equal type |
| >        | Greater than                      |
| <        | Less than                         |
| >=       | Greater than or equal to          |
| <=       | Less than or equal to             |
| ?        | Ternary operator                  |

```js
console.log(3 == 3); // hasilnya true
console.log(3 == '3'); // hasilnya true
console.log(3 === '3'); // hasilnya false
console.log(3 != 4); // hasilnya true
console.log(3 !== '3'); // hasilnya true
console.log(3 > 2); // hasilnya true
console.log(3 < 2); // hasilnya false
console.log(3 >= 3); // hasilnya true
console.log(3 <= 4); // hasilnya true
```

## Logical operators

| Operator | Description |
| -------- | ----------- |
| &&       | And         |
| \|\|     | Or          |
| !         |   Not          |

```js
console.log(true && true); // hasilnya true
console.log(true && false); // hasilnya false
console.log(false && true); // hasilnya false
console.log(false && false); // hasilnya false

console.log(true || true); // hasilnya true
console.log(true || false); // hasilnya true
console.log(false || true); // hasilnya true
console.log(false || false); // hasilnya false

console.log(!true); // hasilnya false
console.log(!false); // hasilnya true

```
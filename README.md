# Lab2Web
```
Nama   : maulana Malik Ibrahim
Nim    : 312410185
Kelas  : TI.24.A2
```

# Tugas 1

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.   
   ```css
   body {
    font-family: 'Open Sans', sans-serif;
    background-color: #f0f0f0;
   }
   h1 {
    font-size: 28px;
    color: darkblue;
    text-transform: uppercase;
    letter-spacing: 2px;
   }
   p {
    color: #444;
    line-height: 1.6;
   }
   ```
   
2. Apa perbedaan pendeklarasian CSS elemen **h1 {...}** dengan **#intro h1 {...}**? berikan penjelasannya!   
   - `h1 { ... }` → berlaku untuk semua elemen `<h1>` di halaman.
   - `#intro h1 { ... }` → hanya berlaku untuk `<h1>` yang ada di dalam elemen dengan `id="intro"`.  
   *Contoh*
  ```css
     h1 { color: red; }
     #intro h1 { color: blue;}
```

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!   
   - Urutan prioritas: **Inline > Internal > Eksternal**.
   *Contoh*
```html
<head>
    <link rel="stylesheet" href="style.css">
    <style>
        p { color: green; }
    </style>
</head>
<body>
    <p style="color: red;">Teks Contoh</p>
</body>
```

4.  Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`   
*Contoh*
```html
<p id="paragraf-1" class="text-paragraf">Teks Contoh</p>
```
```css
.text-paragraf { color: green; }
#paragraf-1 { color: blue; }
```

# Tugas 2
- _Tahap pertama_

 <img width="975" height="502" alt="Image" src="https://github.com/user-attachments/assets/bebb9139-487b-4791-8d1a-6bc5ed24b3f1" />

 <img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/3aa74284-b9cd-44af-a66a-984700673610" />

 - _Tahap Kedua_

   

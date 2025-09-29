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
- # _Tahap pertama_
<img width="975" height="502" alt="Image" src="https://github.com/user-attachments/assets/bebb9139-487b-4791-8d1a-6bc5ed24b3f1" />
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/3aa74284-b9cd-44af-a66a-984700673610" />


 - # _Tahap Kedua_
<img width="990" height="417" alt="Image" src="https://github.com/user-attachments/assets/9a82898a-22aa-4373-9a1d-0522ba46e276" />
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/de835132-8aaa-4efd-b668-1b5c34d71ecc" />


- # _Tahap Ketiga_
<img width="990" height="161" alt="Image" src="https://github.com/user-attachments/assets/3eb010cc-cc98-42ba-b4df-731581d4d703" />
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/e959814c-7d3c-4192-96d7-ea957b62ff64" />


- # _Tahap Keempat_
<img width="990" height="103" alt="Image" src="https://github.com/user-attachments/assets/99dcaf2d-04e9-4336-8d84-3095e29247a1" />
<img width="621" height="523" alt="Image" src="https://github.com/user-attachments/assets/68da3ada-9348-4fa6-be54-bc8903c8d98c" />
<img width="976" height="516" alt="Image" src="https://github.com/user-attachments/assets/608afca9-d132-4ac0-9407-3c21908cb997" />


- # _Tahap Kelima_
<img width="621" height="242" alt="Image" src="https://github.com/user-attachments/assets/55a6842b-4ac4-40e4-98ef-27f845c51590" />
<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/2dc36b49-cb53-4ed1-9e09-a99771c594f7" />

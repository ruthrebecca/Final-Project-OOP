# Sudoku Game

This repository is a final project (Java GUI) from Object-Oriented Programming Class, Teknik Informatika Universitas Padjadjaran. 

[Challenge Guidelines](challenge-guideline.md)

**Sudoku Game adalah sebuah teka-teki angka yang pada umumnya terdiri dari 3 sub-kotak yang berukuran 3x3 (kotak berukuran total 9x9). Aturan dalam permainan Sudoku ini adalah pemain harus mengisi teka-teki dengan aturan tidak boleh terdapat angka yang sama pada satu baris, atau satu kolom, atau satu sub-kotak yang sama. Project Sudoku Game ini menggunakan java GUI (Graphic User Interface) dalam tampilannya dan menggunakan konsep OOP (Object Oriented Programming).**

## Credits
| NPM           | Name        |
| ------------- |-------------|
| 140810190054  | Ruth Rebecca Ovelin    |
| 140810190064  | Yuela Thahira    |
| 140810190076  | Dimas Rahadian Nugraha |

## Change log
- **[Sprint Planning](changelog/sprint-planning.md) - (17/11/2020)** 
   -  Diskusi pembagian kerja project Sudoku
   - Belajar mengenai Sudoku dan mencari referensi

- **[Sprint 1](changelog/sprint-1.md) - (17/11/2020 - 23/11/2020)** 
   - Membuat tampilan grid 9x9 (dengan subgrid 3x3)
   - Implementasi OOP dasar
   - Mengacak angka (clue)

- **[Sprint 2](changelog/sprint-2.md) - (24/11/2020 - 30/11/2020)** 
   - Menampilkan soal (clue) beserta kolom jawaban
   - Membuat tombol submit
   - Mengecek jawaban yang telah diinput
   - Meenampilkan kunci jawaban
   
- **[Sprint 3](changelog/sprint-3.md) - (1/12/2020 - 7/12/2020)** 
   - Memperbaiki tampilan / interface (finishing)
   - Menambah tombol restart & reset   
   - Memberi highlight pada angka yang terdapat pada 1 baris atau 1 kolom atau 1 kotak yang sama 
   - Menambah menu bar
   - Menambah timer  
   - Menambah action pause 
   - Menu high score dengan nama pemain 

## Running The App
   - Compile file GUI.java (javac GUI.java)
   - Jalankan file program GUI (java GUI)

## Classes Used

TO;DO

UML image here

## Notable Assumption and Design App Details

   - Tampilan interface Sudoku akan muncul (grid 9 x 9 dengan subgrid 3 x 3 beserta menu dan tampilan lainnya)
   - User dapat melakukan input angka terhadap grid yang editable sesuai dengan level, dimana semakin sulit levelnya maka semakin banyak pula grid/tile yang harus diisi
   - Klik enter untuk memasukkan angka sekaligus memeriksa apakah inputan user sudah benar dan sesuai
   - Jika sesuai, maka inputan user akan berwarna hijau. Namun jika sebaliknya, akan berwarna merah dan tile yang berisi angka yang sama dengan inputan user dalam 1 subgrid        akan dihighlight dengan warna merah
   - Jumlah 'Cells remaining' akan terus berkurang beriringan dengan jumlah inputan user yang sesuai dengan jawaban
   - Dalam permainan, user bisa mengakses pilihan menu (File dan Options). Pada menu File, user dapat restart game, reset jawaban, dan exit (keluar). Sedangkan pada menu          Options, user dapat mengganti level permainan (Easy, Medium, Hard)
   - Setelah semua tile/grid terisi dengan benar dan tidak ada lagi 'remaining cells', maka permainan selesai dan akan muncul window dialog 'Congratulations'


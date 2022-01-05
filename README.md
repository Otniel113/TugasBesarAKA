# TugasBesarAKA
Ditujukan untuk Tugas Besar mata kuliah Analisas Kompleksitas Algoritma yang dikerjakan secara kelompok 2 orang dengan Jose Vernando

## Deskripsi Singkat
Program ini untuk membandingkan kompleksitas dari 2 algoritma sorting : BubbleSort dan MergeSort di mana kompleksitas masing-masing adalah O(n^2) dan O(n log n). Kedua algoritma sorting tersebut dapat dirasakan perbedaannya untuk inputan (berupa panjang array) yang sangat besar.

## File-file
Kodingan terdapat di folder Source Code dan juga ada juga file PPT (PowerPoint) dan Laporan (berbentuk PDF) untuk informasi yang lebih lengkap.
Pada Source Code, direkomendasikan untuk membuka MergeBubbleSortV2.cbp menggunakan Codeblocks. Jika tidak punya, maka source code utama terdiri dari 3 file, yaitu :

**1. header.h :** Tempat pendefinisian library, dan function-procedure yang akan dipakai

**2. source.cpp :** Tempat penjelasan dari function-procedure yang telah didefiniskan

**3. main.cpp :** Driver, atau tempat di mana program utama dijalankan

Selain itu, bagi User yang ingin bisa langsung run, dapat pergi ke folder /bin dan bisa langsung menjalankan MergeBubbleSortV2.exe

## Overview
Pertama-tama, User diminta untuk memasukkan input berapa panjang array yang akan dibuat, maka akan dibuatkan array dengan isi random sebanyak inputan dari User. Lalu, User akan menemukan menu utama yang fiturnya akan dijelaskan di bawah. Untuk keluar dari program, User tinggal input angka 9

## Fitur-fitur
1. Tampilkan Array : Untuk menampilkan seluruh anggota array
2. Bubble Sort : Mengurutkan array dengan metode BubbleSort dan juga memberitahu lama waktu eksekusinya (dalam milisecond)
3. Merge Sort  : Mengurutkan array dengan metode MergeSort dan juga memberitahu lama waktu eksekusinya (dalam milisecond)
4. Reset isi Array : Mereset isi anggota dari array
9. Keluar : Untuk keluar dari program

## Hasil Pengamatan
Didaptkan hasil pengamatan berupa waktu eksekusi (dalam detik) dari kedua algoritma tersebut untuk nilai n (panjang array) yang berbeda.
| Input (n) | 10 | 100 | 1000 | 10000 | 100000 | 250000 |
| -- | -- | -- | -- | -- | -- | -- |
| Bubble Sort | 0 | 0 | 0.015 | 0.527 | 54.457 | 332 |
| Merge Sort | 0 | 0 | 0 | 0 | 0.033 | 0.078 |
<br>
Atau bisa dilihat dalam grafik <br>

![AKA_Pengamatan](https://drive.google.com/uc?id=154qh2iMJ5-g0ga2sxWdUHBgIsYeCV4kk)

## Video Penjelasan
Silakan klik gambar di bawah untuk pergi ke link video

[![video](https://img.youtube.com/vi/uhNTlwKRZbc/0.jpg)](https://www.youtube.com/watch?v=uhNTlwKRZbc)

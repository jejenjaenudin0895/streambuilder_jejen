# streambuilder_jejen

A new Flutter project.

## **Praktikum 6: StreamBuilder**

## Getting Started

**Soal 12**

A. Jelaskan maksud kode pada langkah 3 dan 7 !

**langkah ke 3**

kode yang di gunakan berfungsi untuk menghasilkan stream angka acak setiap detik menggunakan Stream.periodic

**langkah ke 7**

pada langkah ke 7 sistem pengkodean menggunakan StreamBuilder yang berguna untuk menampilkan data yang diterima dari stream dalam aplikasi Flutter.

terdapat beberapa sintak dalam pengkodean tersebut diantaranya :

1. StreamBuilder: Digunakan untuk mendengarkan stream (numberStream) dan memperbarui UI setiap kali ada data 
   baru yang diterima.

2. initialData: Nilai awal yang ditampilkan sebelum data pertama diterima dari stream (di sini 0).

3. snapshot: Objek yang digunakan untuk memeriksa status stream. Kamu dapat mengecek apakah ada data atau error 
   yang diterima.

4. hasError: Jika stream menghasilkan error, maka akan menampilkan pesan error.

5. hasData: Jika stream memiliki data, maka akan menampilkan data tersebut dalam bentuk teks dengan ukuran font 
   yang besar.

6. SizedBox.shrink(): Digunakan untuk menampilkan widget kosong ketika tidak ada data.

 B. Capture hasil praktikum Anda berupa GIF dan lampirkan di README.
  Lalu lakukan commit dengan pesan "P5: Jawaban Soal 12".

![Screenshoot streambuilder_jejen](images/JawabanSoal12.png)



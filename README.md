# Pertemuan 05 Perulangan Python

Nama: Azizah Nur Kholishah 
NIM: 2225250116
Kelas: 3E

## Tujuan
Menggunakan perulangan for dan while untuk menyelesaikan masalah iteratif dalam Python, khususnya dalam membuat dan menghitung jumlah deret aritmetika.

## Cara Menjalankan
python3 kuis/kuis2_deret_aritmetika.py

## Algoritma Kuis 2
1. Program meminta pengguna memasukkan suku pertama (a) dan beda (d).
2. Program meminta pengguna memasukkan banyak suku (n).
3. Jika n kurang dari atau sama dengan 0, program akan meminta pengguna memasukkan kembali nilai n sampai diperoleh bilangan bulat positif.
4. Variabel total diinisialisasi dengan nilai 0.
5. Perulangan for dilakukan sebanyak n kali.
6. Pada setiap perulangan, nilai suku dihitung berdasarkan suku pertama, beda, dan urutan suku.
7. Setiap nilai suku ditambahkan ke variabel total.
8. Program menampilkan nomor dan nilai setiap suku.
9. Setelah perulangan selesai, program menampilkan jumlah seluruh suku dengan dua angka di belakang koma.

## Hasil Pengujian

| a | d | n | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|---|---|
| 2 | 3 | 5 | 2, 5, 8, 11, 14; Jumlah = 40.00 | 2, 5, 8, 11, 14; Jumlah = 40.00 | Berhasil |
| 10 | -2 | 4 | 10, 8, 6, 4; Jumlah = 28.00 | 10, 8, 6, 4; Jumlah = 28.00 | Berhasil |
| 1.5 | 0.5 | 3 | 1.5, 2.0, 2.5; Jumlah = 6.00 | 1.5, 2.0, 2.5; Jumlah = 6.00 | Berhasil |

## Refleksi

Kesalahan yang dapat terjadi pada program perulangan adalah menentukan batas iterasi pada for. 
Pada awalnya range(n) dapat membingungkan karena dimulai dari 0 sampai n-1. 
Kesalahan tersebut diperbaiki dengan melakukan tracing nilai i setiap iterasi dan menggunakan i+1 
untuk menampilkan nomor suku mulai dari 1. Dengan cara tersebut jumlah iterasi tetap sesuai dengan n 
dan program berjalan dengan benar.
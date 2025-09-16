# Tugas 4 Praktikum Algoritma dan Pemrograman 2025: Function

**PENTING: DIWAJIBKAN UNTUK MENGGUNAKAN FUNCTION UNTUK SEMUA TUGAS BERIKUT DAN TUGAS-TUGAS KEDEPANNYA**

**Penting Juga: Biasakan menambah format berikut pada bagian paling atas setiap file kode!**

```cpp
/*
Nama Program :
Nama         :
NPM          :
Tanggal Buat :
Deskripsi    :
*/
```

## Daftar Isi
- [Latihan 1](#latihan-1)
- [Latihan 2](#latihan-2)
- [Latihan 3](#latihan-3)
- [maxMin!](#maxmin)
- [Desimal ke Oktal](#desimal-ke-oktal)
- [Balikin Angkanya!](#balikin-angkanya)
- [Persamaan Kuadrat](#persamaan-kuadrat)



## Latihan 1
> file: `latihan_1.cpp`

### Deskripsi
Zahra adalah seorang pegawai yang bekerja di sebuah pabrik. Ia ingin membuat program yang dapat menghitung waktu pulangnya setiap hari dengan menginput jam dan menit saat ia mulai bekerja. Ia tahu bahwa ia harus menambahkan 8 jam 30 menit ke jam dan menit yang ia input.

Bantulah Zahra untuk membuat program tersebut dengan menggunakan fungsi `void` yang menerima dua parameter, jam dan menit, dengan tipe data int dan metode *pass by reference* untuk mengubah nilai variabel yang diberikan.

### Format Input
Bilangan bulat positif $h$ dan $m$.

### Format Output
$h$ dan $m$ 8 jam 30 menit kemudian.

### Contoh
  
* Sample Input 1
  
  ```
  2 2
  ```

* Sample Output 1
  
  ```
  10 32
  ```

* Sample Input 2
  
  ```
  10 31
  ```

* Sample Output 2
  
  ```
  19 1
  ```

## Latihan 2
> file: `latihan_2.cpp`

### Deskripsi
Kiki adalah seorang siswa yang sedang belajar tentang deret aritmatika. Ia ingin membuat program sigma yang dapat menghitung nilai  
$\displaystyle\sum_{n=0}^{n} n^m + c$  
di mana $n$ dan $m$ adalah bilangan bulat positif lalu $c$ adalah bilangan real. Bantulah Kiki untuk membuat program sigma menggunakan fungsi yang menerima tiga parameter, $n$, $m$, dan $c$ lalu menampilkan hasilnya.  

### Catatan:
**Tidak boleh** menggunakan `std:pow()` untuk perpangkatan!

### Format Input
Bilangan bulat positif $n$ dan $m$ lalu bilangan bulat positif $c$.

### Format Output
Hasil kalkulasi dari fungsi matematika diatas.

### Contoh
  
* Sample Input 1
  
  ```
  4 4 2
  ```

* Sample Output 1
  
  ```
  364
  ```
    
* Sample Input 2
  
  ```
  7 3 -12.4
  ```

* Sample Output 2
  
  ```
  684.8
  ```

## Latihan 3
> file: `latihan_3.cpp`

### Deskripsi
Diberikan sebuah bilangan bulat positif $n$, kembalikan nilai true jika n adalah pangkat empat ($n = 4^x$). Jika tidak, kembalikan nilai false. Program wajib menggunakan fungsi!

### Format Input
Sebuah bilangan bulat positif $n$.

### Format Output
Nilai true (1) jika n adalah pangkat empat. Jika tidak, kembalikan nilai false (0).

### Contoh
  
* Sample Input 1

  
  ```
  13
  ```

* Sample Output 1

  
  ```
  0
  ```
    
* Sample Input 2

  
  ```
  256
  ```

* Sample Output 2

  
  ```
  1
  ```

## convertTemperature
> file: `tugas_1.cpp`

### Deskripsi
Buatlah program dengan tiga **fungsi**:  
- `toCelsius(double f)` untuk mengubah Fahrenheit ke Celsius  
- `toFahrenheit(double c)` untuk mengubah Celsius ke Fahrenheit  
- `toKelvin(double c)` untuk mengubah Celsius ke Kelvin  

Program membaca sebuah bilangan real dan sebuah karakter yang menunjukkan jenis input suhu (`C` atau `F`). Lalu, program mencetak hasil konversi ke dua satuan lainnya.  

### Format Input
Sebuah bilangan real (nilai suhu) dan sebuah karakter (`C` atau `F`).  

### Format Output
Hasil konversi suhu ke dua satuan lainnya, masing-masing di baris baru.  

### Contoh

* Sample Input 1

  ```
  100 C
  ```

* Sample Output 1

  ```
  Fahrenheit: 212
  Kelvin: 373.15
  ```

* Sample Input 2

  ```
  32 F
  ```

* Sample Output 2

  ```
  Celsius: 0
  Kelvin: 273.15
  ```

  
## weirdMultiply
> file: `tugas_2.cpp`

### Deskripsi
Buatlah fungsi `weirdMultiply(int a, int b)` yang mengembalikan hasil perkalian dua bilangan bulat dengan aturan:
- Jika salah satu bilangan negatif → hasil dikali 2
- Jika keduanya positif → hasil dikurangi 3

Program membaca dua bilangan bulat, lalu mencetak hasil `weirdMultiply`.

### Format Input
Dua bilangan bulat $a$ dan $b$.

### Format Output
Sebuah bilangan bulat hasil weirdMultiply.

### Contoh
* Sample Input 1
```
4 5
```
* Sample Output 1
```
17
```
* Sample Input 2
```
-3 6
```
* Sample Output 2
```
-36
```


## Balikin Angkanya!
> file: `tugas_3.cpp`

### Deskripsi
Ridwan adalah seorang anak yang suka bermain dengan angka. Suatu hari, ia mendapat tantangan dari temannya untuk membuat sebuah program yang dapat melakukan hal berikut:

- Menerima dua bilangan bulat $x$ dan $y$ sebagai input
- Membalikkan urutan digit-digit A dan B, sehingga menjadi $x'$ dan $y'$
- Menjumlahkan $x'$ dan $y'$, sehingga menjadi $z$
- Membalikkan urutan digit-digit $z$, sehingga menjadi $z'$
- Mencetak $z'$ sebagai output

### Format Input
Sebuah bilangan bulat positif $x$ dan $y$

### Format Output
Sebuah bilangan bulat positif $z$ yang sudah dibalik urutannya

### Contoh
  
* Sample Input 1

  
  ```
  342 211
  ```

* Sample Output 1

  
  ```
  553
  ```
    
* Sample Input 2

  
  ```
  69 91
  ```

* Sample Output 2

  
  ```
  511
  ```

## Persamaan Kuadrat
> file: `tugas_3_freeform.cpp`

### Deskripsi
Implementasikan rumus berikut ini ke dalam sebuah fungsi:  
<img src="https://i.ibb.co/w7c6Bc0/eq.png" width="370" height="100">  

### Catatan  
- **Tidak boleh** menggunakan `std:sqrt()` bawaan `cmath` untuk kalkulasi rumus tersebut! Buat fungsi baru agar memudahkan pengerjaan.
- Jawaban **tidak perlu 100% akurat** karena kalian mengimplementasikan fungsi akar kuadrat sendiri


### Format Input dan Output
> Tidak ada format input dan output pada tugas yang bersifat *freeform*. Selama program kamu melakukan yang diinstruksikan, kreasikan sebebasmu! 

### Constraint
  
* Tiga bilangan yang dimasukkan ketiganya muat dalam tipe data bilangan real.

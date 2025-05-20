Penjelasan Jawaban Ujian Tengah Semester 2 (UTS) 

1. Dalam sistem e-commerce, struktur kontrol percabangan digunakan untuk menentukan apakah pelanggan berhak mendapatkan diskon berdasarkan total belanja mereka. Berikut     
   adalah penjelasan mengenai bagaimana logika ini diterapkan:

Struktur Kontrol Percabangan
 1).Input Total Belanja:
    Pertama, sistem meminta input dari pelanggan mengenai total belanja mereka.
 2).Percabangan:
    Menggunakan struktur kontrol percabangan (seperti if dalam Python), sistem memeriksa apakah total belanja lebih besar dari Rp500.000. Jika kondisi tersebut terpenuhi       
    (true), maka pelanggan berhak mendapatkan diskon 10%. Jika tidak (false), pelanggan tidak mendapatkan diskon.
 3).Perhitungan Diskon:
    Jika pelanggan memenuhi syarat untuk diskon, sistem menghitung jumlah diskon dengan mengalikan total belanja dengan 10% (0.10).
    Kemudian, sistem mengurangi total belanja dengan jumlah diskon untuk mendapatkan total yang harus dibayar.
 4).Output:
    Sistem menampilkan total belanja awal, jumlah diskon (jika ada), dan total yang harus dibayar setelah diskon.

2. Peran Tipe Data dan Operator dalam Penentuan Kelulusan Siswa
   
   Tipe Data:
 1).Numerik: Digunakan untuk menyimpan nilai ujian (integer atau float) agar dapat dilakukan perhitungan.
 2).Boolean: Hasil perbandingan (lulus atau tidak) yang digunakan dalam percabangan.

   Operator:
 1).Aritmatika: -Penjumlahan (+) untuk menghitung total nilai.
                -Pembagian (/) untuk menghitung rata-rata nilai.
 2).Perbandingan: Operator seperti >= untuk membandingkan rata-rata dengan ambang batas kelulusan (misalnya, 60).

3. Fungsi adalah blok kode yang dirancang untuk melakukan tugas tertentu. Manfaatnya antara lain:

   1). Modularitas
       Kode menjadi lebih terstruktur dan mudah dipahami karena setiap bagian memiliki tugas spesifik.
   2). Reusabilitas
       Fungsi dapat dipanggil berulang kali tanpa perlu menulis ulang logikanya.
   3). Mudah Dikelola dan Diuji
       Kesalahan (bug) lebih mudah dilacak karena fungsi berdiri sendiri.
   4). Meningkatkan Produktivitas
       Mengurangi penulisan kode berulang, mempercepat pengembangan program.

   Cara Kerja Rekursi dalam Menghitung Faktorial
   
   Rekursi adalah teknik di mana fungsi memanggil dirinya sendiri. Dalam menghitung faktorial, prosesnya sebagai berikut:

   1).Basis Kasus: Fungsi harus memiliki kondisi yang menghentikan pemanggilan rekursif. Untuk faktorial, jika n adalah 0 atau 1, hasilnya adalah 1.
   2).Pemanggilan Rekursif: Jika n lebih dari 1, fungsi memanggil dirinya dengan argumen n-1.
   3).Pengembalian Nilai: Setelah mencapai basis kasus, fungsi mengembalikan nilai ke pemanggilan sebelumnya, mengalikan n dengan hasil pemanggilan rekursif.

4. Dalam kasus di mana seorang guru ingin membuat sistem untuk menginput nilai 5 siswa dan mencari nilai tertinggi, penggunaan perulangan dan array sangat berguna. Berikut      adalah penjelasan mengenai keduanya:

  1).Penggunaan Perulangan
     Perulangan (looping) digunakan untuk mengulangi proses input nilai siswa. Dalam hal ini, kita perlu meminta input dari pengguna sebanyak 5 kali (untuk 5 siswa). Dengan       menggunakan perulangan, kita dapat menghindari penulisan kode yang berulang untuk setiap siswa. Misalnya, kita bisa menggunakan perulangan for untuk mengiterasi dari 0       hingga 4 (total 5 iterasi) dan meminta input nilai setiap kali.

  2).Penggunaan Array
     Array (atau list dalam Python) digunakan untuk menyimpan nilai-nilai yang diinputkan. Dengan menyimpan nilai-nilai siswa dalam array, kita dapat dengan mudah mengakses       dan memanipulasi data tersebut. Setelah semua nilai dimasukkan ke dalam array, kita dapat menggunakan fungsi untuk mencari nilai tertinggi dengan membandingkan setiap        elemen dalam array.

5. Berikut adalah langkah-langkah algoritma untuk menyelesaikan masalah menghitung total harga pembelian 3 barang dalam sistem sederhana untuk seorang kasir toko:

   Langkah-langkah Algoritma
   1). Inisialisasi Variabel:
       Buat variabel untuk menyimpan total harga, misalnya total_harga, dan set nilainya ke 0.
   2). Input Harga Barang:
       -Untuk setiap barang (total 3 barang):
       -Minta pengguna (kasir) untuk memasukkan harga barang.
       -Simpan harga barang ke dalam variabel, misalnya harga_barang.
   3). Penjumlahan Harga:
       -Tambahkan harga_barang ke total_harga setelah setiap input.
   4). Tampilkan Total Harga:
       Setelah semua harga barang dimasukkan dan dijumlahkan, tampilkan nilai total_harga kepada pengguna.


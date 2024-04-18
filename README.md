<p align="center">
<img align="center" src="http://ForTheBadge.com/images/badges/built-with-love.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/uses-html.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/makes-people-smile.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/built-by-developers.svg">
</p>

# Aplikasi Berbasis Web Data Penjualan dengan Laravel 8

Membuat Aplikasi Berbasis Web Data Penjualan Menggunakan Laravel 8, Yang Bertujuan Untuk Presentasi Kepada Tester. Aplikasi Berbasis Web Data Penjualan dengan Laravel 8 adalah aplikasi yang berfungsi untuk melakukan pendataan barang.

## Desain ERD

<img src="public/assets_readme/img/Desain_ERD.png" alt="Desain ERD">


## Penjelasan Aplikasi

|<h3>Notes  </h3>       |       Keterangan                                                                  |
|-----------------------|-----------------------------------------------------------------------------------|
|<b>Jenis Penjualan     | </b>Digunakan untuk menyimpan data jenis penjualan.                               |
|<b>Transaksi Penjualan | </b>Digunakan untuk menyimpan data transaksi penjualan. (Master Data Penjualan).  |
|<b>Barang Penjualan    | </b>Digunakan untuk menyimpan data barang penjualan.                              |
|<b>Waktu Transaksi     | </b>Digunakan untuk menyimpan data kapan waktu transaksi.                         |


## Cara Instalasi ke Server Lokal :

-   ketik <b>composser install </b> dan <b>php artisan key generate</b>
-   tulis migrate database pada terminal/cmd/git bash : <b>php artisan migrate:install</b>
-   jalankan php artisan db:seed pada terminal/cmd/git bash : <b>php artisan db:seed</b>

<b>Notes :</b> Untuk db:seed jika males untuk mengetikan data, akan dibuatkan langsung oleh laravelnya.

## Fitur Aplikasi

-   Halaman Utama (Halaman Dashboard)<br><br>

A. Menu Data Jenis Barang<br>

-   Tambah Data (Data Jenis Barang)<br>
-   Ubah Data (Data Jenis Barang)<br>
-   Hapus Data (Data Jenis Barang)<br>

B. Menu Data Master Penjualan<br>

-   Tambah Data (Data Master Penjualan)<br>
-   Ubah Data (Data Master Penjualan)<br>
-   Hapus Data (Data Master Penjualan)<br>

C. Menu Data Log Transaksi<br>

-   Reset Data (Data Log Transaksi)<br>

D. Menu Perbandingan Jenis Data

E. Menu Tambahan

-   Pembuat Website
-   Dokumentasi Singkat

## Alat Yang Digunakan Untuk Membuat Web :

-   WAMP
-   Visual Studio Code
-   Git
-   Cloud (Github)
-   PHP 7.4.9
-   MYSQL 8.0.13
-   Laravel 8
-   Bootstrap 5
-   Composer



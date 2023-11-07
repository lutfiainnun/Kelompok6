**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Sistem Pengelolaan Edotel SMKN 1 Pekanbaru". Dokumen ini dibangun untuk memudahkan pihak pengelola hotel untuk mengelola data pemesanan kamar oleh pelanggan, pencatatan check-in, proses check-out dan daftar kedatangan yang diharapkan yang ada pada unit produksi Edotel SMKN 1 Pekanbaru. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Sistem Pengelolaan Edotel SMKN 1 Pekanbaru".

1.2   Lingkup
----------
Sistem Pengelolaan Edotel merupakan website yang kami bangun untuk mempermudah pengelola hotel dalam mengelola data pemesanan kamar oleh pelanggan, pencatatan check-in, proses check-out dan daftar kedatangan yang diharapkan sehingga proses pengeloaan hotel berjalan dengan efektif dan efisien.

1.3    Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses website |
| Software Requirement Specification | Perangkat lunak yang akan dibuat dan sebagai menjembatani komunikasi pembuat dengan pengguna |
| Use Case | Situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4   Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada Website. Menjelaskan gambaran umum dari website, sistem interface website dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari website yang akan diterapkan pada website yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari dalam studi kasus proyek ini kami menganalisis kebutuhan suatu unit produksi sekolah di daerah Pekanbaru yaitu SMKN 1 Pekanbaru. Kasus yang kami peroleh adalah pengelolaan unit produksi yaitu Edotel. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan sekolah SMKN 1 Pekanbaru dengan menerapkan manajemen data Edotel. Sehingga memudahkan resepsionis dalam mengelola proses berjalannya Edotel. Software yang kami buat ini berbasis website. Sistem yang kami buat di dalamnya terdapat informasi pemesanan kamar, pencatatan check-in, proses check-out serta daftar kedatangan yang diharapkan. Berikut akan kami jelaskan sistem software kami, resepsionis Edotel fungsi utama yaitu :

   - Input Informasi Pemesanan Kamar 
   - Input Pencatatan Check-in
   - Input Proses Check-out
   - Input Daftar Kedatangan Yang Diharapkan
   
   Berikut ini fungsi Kepala Edotel:
   
   - View Pencatatan Barang Masuk
   - View Pencatatan Barang keluar
   - View Laporan pemasukan dan pengeluaran stok barang

2.1   Perspektif produk
----------
Sistem Pengelolaan Edotel adalah sebuah sistem pengelolaan data yang di aplikasiskan pada website. Terdapat 2 jenis yaitu resepsionis dan kepala hotel. Pengolahan data di kelola oleh resepsionis dan kepala hotel hanya melihat grafik dan laporan pada website.

Pada sistem pengelolaan data hotel ini akan menampilkan grafik kependudukan yang sudah di inputkan oleh admin.

**2.1.1 Antarmuka sistem**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/antarmuka%20sistem1.png)

Sistem Pengelolaan Edotel SMKN 1 Pekanbaru memiliki 2 user yaitu resepsionis dan kepala hotel. Kepala hotel mempunyai fungsi yaitu melakukan view grafik dan bisa view laporan. Resepsionis bertugas untuk mengelola data, supaya data bisa di akses oleh kepala hotel.

**2.1.2 Antarmuka pengguna**

   - **Mockup Resepsionis ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Login.png) Pada halaman login staff diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Halaman%20Utama%20Data%20Barang.png) Pada halaman data barang terdapat tabel yang berisi nama barang, stock barang, aksi, fitur pencarian dan tombol tambah barang serta ucapan selamat datang.|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tampilan%20Tambah%20Data%20Barang.png) Pada halaman tambah data barang dapat menginputkan data barang baru| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tampilan%20Edit%20Data%20Barang.png) Pada halaman edit data barang dapat mengubah data barang yang telah ada| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tampilan%20Delete%20Data%20Barang.png) Pada halaman delete data barang dapat menghapus data barang|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Barang%20Masuk.png) Pada halaman barang masuk dapat menginputkan data barang yang masuk sebagai penambahan stok barang| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Barang%20Keluar.png) Pada halaman barang keluar dapat melihat barang keluar atau yang telah digunakan|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Laporan.png) Pada halaman laporan dapat melihat dan mendownload laporan penduduk||

**2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/antarmuka%20perangkat%20keras.png)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Inventory Laundry SMKN 1 Pekanbaru antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .
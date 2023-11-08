<html>
<p align="center">
<img src="https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Software%20Requirements%20Specification-1%20(2)_page-0001.jpg"/ >
</p>
</html>

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Sistem Pengelolaan Edotel SMKN 1 Pekanbaru". Dokumen ini dibangun untuk memudahkan pihak pengelola hotel untuk mengelola data pemesanan kamar oleh pelanggan, pencatatan check-in, proses check-out dan daftar kedatangan yang diharapkan yang ada pada unit produksi Edotel SMKN 1 Pekanbaru. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Sistem Pengelolaan Edotel SMKN 1 Pekanbaru".

1.2   Lingkup
----------
Sistem Pengelolaan Edotel merupakan website yang kami bangun untuk mempermudah pengelola hotel dalam mengelola data pemesanan kamar oleh pelanggan, pencatatan check-in, proses check-out dan daftar kedatangan yang diharapkan sehingga proses pengeloaan hotel berjalan dengan efektif dan efisien.

1.3    Akronim, Singkatan, Definisi
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

   - Input Informasi Kamar 
   - Input Pencatatan Check-in
   - Input Proses Check-out
   - Input Data Kamar
   
   Berikut ini fungsi Manager Edotel:
   
   - View Laporan Transaksi/Pendapatan

2.1   Perspektif produk
----------
Sistem Pengelolaan Edotel adalah sebuah sistem pengelolaan data yang di aplikasiskan pada website. Terdapat 2 jenis yaitu resepsionis dan manager hotel. Pengolahan data di kelola oleh resepsionis dan manager hotel hanya melihat laporan pada website.

**2.1.1 Antarmuka sistem**

![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/antarmuka%20sistem%201.png)

Sistem Pengelolaan Edotel SMKN 1 Pekanbaru memiliki 2 user yaitu resepsionis dan manager hotel. Manager hotel mempunyai fungsi yaitu melakukan view laporan. Resepsionis bertugas untuk mengelola data, supaya data bisa di akses oleh manager hotel.

**2.1.2 Antarmuka pengguna**

   - **Mockup Resepsionis ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Login%20(1).png) Pada halaman login user diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Dashboard.png) Pada halaman dashboard akan menampilkan kamar yang tersedia, terpakai serta yang kotor, dll.| 
![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Informasi%20kamar.png) Pada halaman informasi kamar terdapat tabel yang berisi segala informasi tentang kamar.| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tambah%20data%20kamar.png) Pada halaman tambah data kamar dapat menginputkan data kamar baru| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tampilan%20Check%20In.png) Pada halaman check in terdapat pilihan kamar yang tersedia| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tambah%20data%20tamu.png) Pada halaman ini terdapat form data tamu yang harus diisi jika ingin check in.|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tampilan%20check%20out.png) Pada halaman ini terdapat daftar kamar yang terpakai| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Check%20out.png) Pada halaman ini terdapat form data tamu yang harus diisi jika ingin check out.|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Laporan%20transaksi.png) Pada halaman laporan dapat melihat total pendapatan||

**2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/antarmuka%20perangkat%20keras%201.png)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Pengelolaan Edotel SMKN 1 Pekanbaru antara lain:

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser.

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Pengelolaan Edotel SMKN 1 Pekanbaru antara lain :
1. Kabel Lan UTP RJ45
2. Modem
3. Wifi

**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses website |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak laporan |

**2.1.8 Kebutuhan adaptasi**

Tidak ada

2.2 Spesifikasi Kebutuhan fungsional
----------

BELUM ADA USE CAASE





2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm  OS ( Staff dan kepala laundry ) 
 
2.4   Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6   Asumsi-asumsi
----------
Maksimal penginputan id atau memasukkan kode pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan "Anda telah melebihi batas maksimum".

2.7   Kebutuhan Penyeimbang
----------
Tidak ada

BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses aplikasi ini yaitu login melalui website ini dengan mencantumkan username kemudian sistem akan mencocokkan username staff. Setelah login berhasil staff dapat melakukan pengolahan data pada website Inventory Laundry SMKN 1 Pekanbaru.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1

TERGANTUNG USE CASE

3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem website Inventory Laundry SMKN 1 Pekanbaru terdapat struktur Database yang dijelaskan menggunakan ERD.

BELUM ADA ERD

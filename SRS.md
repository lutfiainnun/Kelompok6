**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Inventory Laundry SMKN 1 Pekanbaru". Dokumen ini dibangun untuk memudahkan pihak sekolah untuk menginput data-data mengenai stock persediaan barang yang ada pada unit produksi laundry SMKN 1 Pekanbaru. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Inventory Laundry SMKN 1 Pekanbaru".

1.2   Lingkup
----------
Sistem Inventory Laundry merupakan website yang kami bangun untuk mempermudah staf dalam mengelola persediaan barang maupun peralatan yang dibutuhkan dalam menjalankan usaha laundry yang ada di SMKN 1 Pekanbaru seperti deterjen, pelembut kain, bahan kimia pencucian, pengharum pakaian, hanger, kemasan, hingga peralatan seperti mesin cuci, mesin pengering, dan peralatan penyetrikaan.

1.3    Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses website |
| Software Requirement Specification | Perangkat lunak yang akan dibuat dan sebagai menjembatani komunikasi pembuat dengan pengguna |
| Use Case | Situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.5   Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada Website. Menjelaskan gambaran umum dari website, sistem interface website dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari website yang akan diterapkan pada website yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari dalam studi kasus Proyek ini kami menganalisis kebutuhan suatu Sekolah di daerah Pekanbaru yaitu SMKN 1 Pekanbaru. Kasus yang kami peroleh adalah pembuatan laporan mengenai inventory laundry. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan sekolah SMKN 1 Pekanbaru dengan menerapkan manajemen data inventory laundry. Sehingga memudahkan staff dalam menginputkan data barang persediaan serta mengecek stock barang yang tersedia maupun yang berkurang. Software yang kami buat ini berbasis website. Sistem yang kami buat di dalamnya terdapat pencatatan persediaan barang, pencatatan barang yang digunakan, pencatatan persediaan yang dikeluarkan, laporan pemasukan barang serta pengeluaran stok barang. Berikut akan kami jelaskan sistem software kami, staff laundry fungsi utama yaitu :

   - Input Pencatatan Barang Masuk
   - Input Pencatatan Barang keluar
   - Input Pencatatan Permintaan Barang
   - Laporan pemasukan dan pengeluaran stok barang
   
   Berikut ini fungsi kepala laundry dalam bentuk tabel:
   
   - View Pencatatan Barang Masuk
   - View Pencatatan Barang keluar
   - View Pencatatan Permintaan Barang
   - View Laporan pemasukan dan pengeluaran stok barang

2.1   Perspektif produk
----------
Inventory Laundry adalah perangkat lunak atau platform yang dirancang untuk membantu bisnis laundry mengelola persediaan mereka. Terdapat 2 jenis yaitu staff dan kepala laundry. Pengolahan data di kelola oleh staff dan kepala laundry hanya melihat laporan pada website.

Pada sistem inventory laundry ini akan menampilkan tabel persediaan barang yang sudah diinputkan oleh staff.

**2.1.1 Antarmuka sistem**

![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/antarmuka%20sistem.png)

Sistem website Inventory Laundry SMKN 1 Pekanbaru memiliki 2 user yaitu staff dan kepala laundry.

**2.1.2 Antarmuka pengguna**

   - **Mockup Staff ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Login.png) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Dashboard.png) Pada Dashboard admin terdapat panel-panel seperti penduduk, pendidikan, agama, pekerjaan, laporan dan ucapan selamat datang.|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Dropdone%20Kependudukan.png) Pada halaman dashboard ada navigation bar kependudukan yang berisi dropdown angka kelahiran dan angka kematian| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Agama.png) Pada Halaman agama dapat menginputkan data agama penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Pekerjaan.png) Pada Halaman pekerjaan dapat menginputkan data pekerjaan penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Warga.png) Pada Halaman warga dapat menginputkan data warga|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Pendidikan.png) Pada Halaman pendidikan dapat menginputkan data pendidikan penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Angka%20Kelahiran.png) Pada Halaman kelahiran dapat menginputkan data kelahiran penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Angka%20Kematian.png) Pada Halaman kematian dapat menginputkan data kematian penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Grafik%20Angka%20kelahiran.png) Pada Halaman grafik kelahiran dapat melihat data angka kelahiran|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Grafik%20Angka%20kematian.png) Pada Halaman grafik kematian dapat melihat data angka kematian| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Laporan.png) Pada Halaman laporan dapat melihat dan mendownload laporan penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Lupa%20Password.png) Pada halaman lupa password dapat mengganti password terlebih dahulu memasukkan username dan password sebelumnya| |

**2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/antarmuka%20perangkat%20keras.png)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Inventory Laundry SMKN 1 Pekanbaru antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Inventory Laundry SMKN 1 Pekanbaru antara lain :
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
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case.png)
   
**2.2.1 Kepala Laundry Login**

Use Case: Login

Diagram : 
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20login%20keplau.png)

Deskripsi Singkat
Kepala laundry melukan login terlebih dahulu sebelum masuk ke tampilan home.
Deskripsi langkah-langkah
1. Kepala laundry melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Login Kepala Laundry

**2.2.2 Kepala laundry melihat laporan barang**

Use Case: View laporan barang

Diagram: 
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20kepdes%20generate%20laporan.png)

Deskripsi Singkat
Kepala laundry dapat melihat laporan barang secara bulanan di Laundry SMKN 1 Pekanbaru.
Deskripsi Langkah-langkah
1. Kepala laundry mengklik navbar laporan
2. Kepala laundry memilih combobox tersebut dan klik tombol cetak laporan
3. Sistem akan menampilkan hasil laporan.

Xref: Bagian 3.2.2, View laporan barang

**2.2.3 Staff login**

Use Case: Login

Diagram :
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20login.png)

Deskripsi Singkat
Staff melakukan login dengan memasukan username password.
Deskripsi Langkah-langkah
1. Staff melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.3, Login Staff

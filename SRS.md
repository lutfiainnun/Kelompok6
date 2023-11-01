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
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20laporan%20keplau.png)

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
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20login%20staff.png)

Deskripsi Singkat
Staff melakukan login dengan memasukan username password.
Deskripsi Langkah-langkah
1. Staff melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.3, Login Staff

**2.2.4 Staff input data barang**

Use Case: Input data barang

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20data%20barang%20staff.png)
      
Deskripsi Singkat
Staff melakukan input data barang yang biasanya digunakan untuk proses laundry dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Staff melakukan input data barang.
2. Staff mengklik tombol simpan.
3. Sistem menyimpan data kependudukan.
4. Bila data sudah ada sistem akan menampilkan peringatan

Xref: Bagian 3.2.4, Input data barang

**2.2.5 Staff input data barang masuk**

Use Case: Input data barang masuk

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20barang%20masuk%20staff.png)
      
Deskripsi Singkat
Staff melakukan input data barang yang masuk untuk tambahan stock barang dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Staff melakukan input data barang masuk.
2. Staff mengklik tombol simpan.
3. Sistem menyimpan data kependudukan.
4. Bila data sudah ada sistem akan menampilkan peringatan

Xref: Bagian 3.2.5, Input data barang masuk

**2.2.6 Staff input data barang keluar**

Use Case: Input data barang keluar

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20barang%20keluar%20staff.png)
      
Deskripsi Singkat
Staff melakukan input data barang keluar atau barang yang telah digunakan untuk proses laundry dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Staff melakukan input data barang keluar.
2. Staff mengklik tombol simpan.
3. Sistem menyimpan data kependudukan.
4. Bila data sudah ada sistem akan menampilkan peringatan

Xref: Bagian 3.2.6, Input data barang keluar

**2.2.7 Staff input data permintaan barang**

Use Case: Input data permintaan barang

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20permintaan%20barang%20staff.png)
      
Deskripsi Singkat
Staff melakukan input data permintaan barang dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Staff melakukan input data permintaan barang.
2. Staff mengklik tombol simpan.
3. Sistem menyimpan data kependudukan.
4. Bila data sudah ada sistem akan menampilkan peringatan

Xref: Bagian 3.2.7, Input data permintaan barang


**2.2.8 Staff melihat data barang**

Use Case: View data barang

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20lihat%20data%20barang%20staff.png)

Deskripsi Singkat
Staff dapat melihat data barang setelah di inputkan.
Deskripsi Langkah-langkah
1. Sistem akan menampilkan data barang Laundry SMKN 1 Pekanbaru.
2. Staff melihat data dan dapat mengedit atau menghapusnya.
3. Sistem menampilkan edit data barang
4. Staff  mengedit data barang yang baru atau yang sudah ada
5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan

Xref: Bagian 3.2.8, View data barang
   
**2.2.9 Generate Laporan**

Use Case: Laporan

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20laporan%20staff.png)

Deskripsi Singkat
Sistem akan mengirimkan data kependudukan dan yang lainnya ke fungsi laporan
Deskripsi Langkah-langkah
1. Sistem menampilkan laporan kependudukan
2. Staff memilih combobox tersebut dan klik tombol cetak
3. Sistem akan menampilkan hasil laporan.
4. Staff mencetak laporan 

Xref: Bagian 3.2.9, Cetak Laporan

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
Salah satu cara mengakses aplikasi ini yaitu login melalui website ini dengan mencantumkan username kemudian sistem akan mencocokkan username staff dan kepala laundry. Setelah login berhasil kepala laundry dapat melihat laporan data barang Laundry SMKN 1 Pekanbaru.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1

**3.2.1 Kepala laundry Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Kepala laundry |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Halaman login |
| Basic Path | 1. Kepala laundry mengisi form login dengan username dan password <br> 2.Kepala laundry mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Kepala laundry dapat login dan mengakses website Inventory Laundry SMKN 1 Pekanbaru |
| Exception Push | Username dan password salah |
      
**3.2.2 Kepala laundry melihat laporan barang**

|  |  |
|--|--|
| Nama Fungsi | View laporan barang |
| Xref | Bagian 2.2.2, View laporan barang |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Membuka halaman laporan |
| Basic Path | 1. Kepala laundry mengklik navbar laporan <br> 2. Sitem akan menampilkan combobox pilihan bulan dan tahun <br>3. Kepala laundry memilih combobox tersebut dan klik tombol lihat <br> 4. Sistem akan menampilkan hasil laporan. |
| Alternative | Tidak ada |
| Post Condition | Kepala laundry melihat laporan barang |
| Exception Push | Tidak ada koneksi |
   
**3.2.3 Staff login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.3, Login staff |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Halaman login staff |
| Basic Path | 1. Staff melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Staff berhasil login dan mengakses website Inventory Laundry SMKN 1 Pekanbaru |
| Exception Push | Username dan password salah |
   
**3.2.4 Staff input data barang**

|  |  |
|--|--|
| Nama Fungsi | Input data barang |
| Xref | Bagian 2.2.4, Input data barang |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Halaman utama staff |
| Basic Path | 1. Staff melakukan input data barang yang biasanya digunakan untuk proses laundry <br> 2. Staff mengklik tombol simpan <br> 3. Sistem menyimpan data barang <br> 4. Bila data sudah ada sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data barang |
| Exception Push | Tidak ada koneksi |

**3.2.5 Staff input data barang masuk**

|  |  |
|--|--|
| Nama Fungsi | Input data barang masuk |
| Xref | Bagian 2.2.5, Input data barang masuk |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Halaman utama staff |
| Basic Path | 1. Staff melakukan input data barang yang masuk untuk tambahan stock barang <br> 2. Staff mengklik tombol simpan <br> 3. Sistem menyimpan data barang |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data barang masuk |
| Exception Push | Tidak ada koneksi |

**3.2.6 Staff input data barang keluar**

|  |  |
|--|--|
| Nama Fungsi | Input data barang keluar |
| Xref | Bagian 2.2.6, Input data barang keluar |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Halaman utama staff |
| Basic Path | 1. Staff melakukan inpu tdata barang keluar atau barang yang telah digunakan untuk proses laundry <br> 2. Staff mengklik tombol simpan <br> 3. Sistem menyimpan data barang |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data barang keluar |
| Exception Push | Tidak ada koneksi |

**3.2.7 Staff input data permintaan barang**

|  |  |
|--|--|
| Nama Fungsi | Input data permintaan barang |
| Xref | Bagian 2.2.7, Input data permintaan barang |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Halaman utama staff |
| Basic Path | 1. Staff melakukan input data permintaan barang <br> 2. Staff mengklik tombol simpan <br> 3. Sistem menyimpan data barang |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data barang |
| Exception Push | Tidak ada koneksi |
   
**3.2.8 Staff melihat data barang**

|  |  |
|--|--|
| Nama Fungsi | View data barang |
| Xref | Bagian 2.2.8, View data barang |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | Halaman form input data |
| Basic Path | 1. Sistem akan menampilkan data barang Laundry SMKN 1 Pekanbaru. <br> 2. Staff melihat data dan dapat mengedit atau menghapusnya. <br> 3. Sistem menampilkan edit data barang <br>4. Staff  mengedit data barang yang baru atau yang sudah ada<br>5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan|
| Alternative | Tidak ada |
| Post Condition | Halaman data barang |
| Exception Push | Tidak ada koneksi |
   
**3.2.9 Cetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.9, Cetak Laporan |
| Trigger | Membuka website Inventory Laundry SMKN 1 Pekanbaru |
| Precondition | halaman utama staff |
| Basic Path | 1. Staff mengklik tombol laporan <br> 2. Sistem menampilkan laporan kependudukan <br> 3. Staff memilih combobox tersebut dan klik tombol lihat <br>4. Sistem akan menampilkan hasil laporan. <br>5. Staff mencetak laporan  |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |

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
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari dalam studi kasus proyek ini kami menganalisis kebutuhan suatu unit produksi sekolah di daerah Pekanbaru yaitu SMKN 1 Pekanbaru. Kasus yang kami peroleh adalah pengelolaan unit produksi yaitu Edotel. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan sekolah SMKN 1 Pekanbaru dengan menerapkan manajemen data Edotel. Sehingga memudahkan resepsionis dalam mengelola proses berjalannya Edotel. Software yang kami buat ini berbasis website. Sistem yang kami buat di dalamnya terdapat informasi pemesanan kamar, pencatatan check-in, proses check-out serta daftar kedatangan yang diharapkan. Berikut akan kami jelaskan sistem software kami, admin Edotel fungsi utama yaitu :

   - Input Informasi Kamar 
   - Input Pencatatan Check-in
   - Input Proses Check-out
   - Input Data Kamar
   - Input Data Tamu
   - View Laporan Transaksi/Pendapatan

2.1   Perspektif produk
----------
Sistem Pengelolaan Edotel adalah sebuah sistem pengelolaan data yang di aplikasikan pada website. Terdapat admin, pengolahan data di kelola oleh admin.

**2.1.1 Antarmuka sistem**

![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/antarmuka%20sistem%201.png)

Sistem Pengelolaan Edotel SMKN 1 Pekanbaru memiliki 1 user yaitu admin. Admin bertugas untuk mengelola data dan melihat laporan.

**2.1.2 Antarmuka pengguna**

   - **Mockup Resepsionis ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Login(2).png) Pada halaman login user diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Dashboard.png) Pada halaman dashboard akan menampilkan kamar yang tersedia, terpakai serta yang kotor, dll.| 
![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Informasi%20kamar.png) Pada halaman informasi kamar terdapat tabel yang berisi segala informasi tentang kamar.| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tambah%20data%20kamar%20(2).png) Pada halaman tambah data kamar dapat menginputkan data kamar baru| ![enter image description here]
![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tampilan%20Check%20In.png) Pada halaman check in terdapat pilihan kamar yang tersedia.| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tambah%20data%20tamu%20(3).png) Pada halaman ini terdapat form data tamu yang harus diisi jika ingin check in.|
![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Tampilan%20check%20out.png) Pada halaman ini terdapat daftar kamar yang terpakai| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Check%20out%20(1).png) Pada halaman ini terdapat form data tamu yang harus diisi jika ingin check out.|
| ![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/Laporan%20transaksi(2).png) Pada halaman laporan dapat melihat total pendapatan||

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
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/use%20case%20(1).png)

**2.2.1 Admin Login**

Use Case: Login

Diagram :
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/admin%20login.png)

Deskripsi Singkat
Admin melakukan login dengan memasukan username password.
Deskripsi Langkah-langkah
1. Admin melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Login Resepsionis

**2.2.2 Admin Input Data Kamar**

Use Case: Input data kamar

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/admin%20data%20kamar.png)
      
Deskripsi Singkat
Admin melakukan input data kamar yang tersedia di Edotel dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Admin melakukan input data kamar.
2. Admin mengklik tombol simpan.
3. Sistem menyimpan data barang.
4. Bila data sudah ada sistem akan menampilkan peringatan

Xref: Bagian 3.2.2, Input data kamar

**2.2.3 Resepsionis Input Data Check In**

Use Case: Input data check in

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/admin%20check%20in.png)
      
Deskripsi Singkat
Admin melakukan input data check in untuk reservasi pelanggan dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Admin melakukan input data-data yang diperlukan untuk check in.
2. Admin mengklik tombol simpan.
3. Sistem menyimpan data check in.
   
Xref: Bagian 3.2.3, Input data check in

**2.2.4 Admin Input Data Check Out**

Use Case: Input data check out

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/admin%20check%20out.png)
      
Deskripsi Singkat
Admin melakukan input data check out untuk reservasi pelanggan dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Admin melakukan input data-data yang diperlukan untuk check out.
2. Admin mengklik tombol simpan.
3. Sistem menyimpan data check out.
   
Xref: Bagian 3.2.4, Input data check out

**2.2.5 Admin Input Data Tamu**

Use Case: Input data tamu

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/admin%20data%20tamu.png)
      
Deskripsi Singkat
Admin melakukan input data tamu yang akan menginap di Edotel dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Admin melakukan input data tamu.
2. Admin mengklik tombol simpan.
3. Sistem menyimpan data tamu.

Xref: Bagian 3.2.5, Input data tamu

**2.2.6 Generate Laporan**

Use Case: Laporan

Diagram:
![](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/admin%20laporan.png)

Deskripsi Singkat
Sistem akan mengirimkan tanggal transaksi serta total biaya kamar dan yang lainnya ke fungsi laporan
Deskripsi Langkah-langkah
1. Sistem menampilkan laporan
2. Admin memilih combobox tersebut dan klik tombol lihat laporan
3. Sistem akan menampilkan hasil laporan.

Xref: Bagian 3.2.6, Laporan

2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm  OS ( Resepsionis dan Manager ) 
 
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
Salah satu cara mengakses aplikasi ini yaitu login melalui website ini dengan mencantumkan username kemudian sistem akan mencocokkan username Admin. Setelah login berhasil Admin dapat melakukan pengolahan data pada website Pengelolaan Edotel SMKN 1 Pekanbaru.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
   
**3.2.1 Admin login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Admin |
| Trigger | Membuka website Pengelolaan Edotel SMKN 1 Pekanbaru |
| Precondition | Halaman login Admin |
| Basic Path | 1. Admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin berhasil login dan mengakses website Pengelolaan Edotel SMKN 1 Pekanbaru |
| Exception Push | Username dan password salah |
   
**3.2.2 Admin input data kamar**

|  |  |
|--|--|
| Nama Fungsi | Input data kamar |
| Xref | Bagian 2.2.2, Input data kamar |
| Trigger | Membuka website Pengelolaan Edotel SMKN 1 Pekanbaru |
| Precondition | Halaman beranda |
| Basic Path | 1. Admin melakukan input data kamar dan lain-lain <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data kamar <br> 4. Bila data sudah ada sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data kamar |
| Exception Push | Tidak ada koneksi |

**3.2.3 Admin Input Data Check In**

|  |  |
|--|--|
| Nama Fungsi | Input data check in |
| Xref | Bagian 2.2.3, Input data check in |
| Trigger | Membuka website Pengelolaan Edotel SMKN 1 Pekanbaru |
| Precondition | Halaman beranda |
| Basic Path | 1. Admin melakukan input data-data yang diperlukan untuk proses check in <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data check in |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data check in |
| Exception Push | Tidak ada koneksi |

**3.2.4 Admin Input Data Check Out**

|  |  |
|--|--|
| Nama Fungsi | Input data check out |
| Xref | Bagian 2.2.4, Input data check out |
| Trigger | Membuka website Pengelolaan Edotel SMKN 1 Pekanbaru |
| Precondition | Halaman beranda |
| Basic Path | 1. Admin melakukan input data-data yang diperlukan untuk proses check out <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data check out |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data check out |
| Exception Push | Tidak ada koneksi |

**3.2.5 Resepsionis input data tamu**

|  |  |
|--|--|
| Nama Fungsi | Input data tamu |
| Xref | Bagian 2.2.5, Input data tamu |
| Trigger | Membuka website Pengelolaan Edotel SMKN 1 Pekanbaru |
| Precondition | Halaman beranda |
| Basic Path | 1. Admin melakukan input data tamu dan lain-lain <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data tamu <br> 4. Bila data sudah ada sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data tamu |
| Exception Push | Tidak ada koneksi |

**3.2.6 Generate Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.6, Generate Laporan |
| Trigger | Membuka website Pengelolaan Edotel SMKN 1 Pekanbaru |
| Precondition | Halaman beranda |
| Basic Path | 1. Admin mengklik tombol laporan <br> 2. Sistem menampilkan laporan transaksi <br> 3. Admin memilih combobox tersebut dan klik tombol lihat <br>4. Sistem akan menampilkan hasil laporan. |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |

3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada website Pengelolaan Edotel SMKN 1 Pekanbaru terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/lutfiainnun/Kelompok6/blob/main/Image%20SRS/erd%20hotel.png)

**Tabel Admin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_resepsionis| int | Nomer auto increment Id_resepsionis|
| Username | varchar | berisikan username untuk akses resepsionis |
| Password | varchar | berisikan password untuk login resepsionis |

**Tabel Kamar**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kamar | varchar | Nomer auto increment Id_kamar|
| no_kamar | int | Nomor kamar|
| Jumlah | int | Jumlah kamar yang tersedia|
| status | varchar | status kamar|
| tipe_kamar | varchar | tipe kamar yang tersedia di Edotel|
| harga | varchar | harga kamar untuk menginap |

**Tabel Reservasi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| tanggal_masuk | date | berisikan tanggal pelanggan melakukan check in |
| tanggal_keluar | date | berisikan tanggal pelanggan melakukan check out |

**Tabel Pelanggan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pelanggan| int | Nomer auto increment Id_pelanggan|
| nama | varchar | berisikan nama pelanggan |
| no_hp | varchar | berisikan no hp pelanggan |
| email | varchar | berisikan email pelanggan |
| alamat | varchar | berisikan alamat pelanggan |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| tanggal_masuk | date | berisikan tanggal pelanggan melakukan check in |
| tanggal_keluar | date | berisikan tanggal pelanggan melakukan check out |
| transaksi | varchar | berisikan data transaksi kamar |
| total | varchar | berisikan total biaya kamar |
----------

**Job Desk**

| Nama | Tugas |
| ------ | ------ | 
| Juniardi | Use Case & ERD | 
| Lutfi Ainnun Fruityantri | SRS, Use Case & ERD | 
| M. Qushairi Asshiddiqie | Antarmuka pengguna | 

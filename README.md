# SIP MBER



## Anggota Kelompok
- Muhammad Sadikin Samir 2409116031
- Muhammad Fachri 2409116017
- Zidan Daffa Ramadhan 2409116056
- Ahmad Qomarul Arifin 2409116114


# Pengenalan SIP MBER
_Platform_ ini dirancang untuk menghadirkan perubahan sosial yang positif melalui teknologi digital dengan tujuan utama meningkatkan kesejahteraan masyarakat berpenghasilan rendah. SIP MBER berfokus pada akses yang mudah terhadap program bantuan, pelatihan keterampilan, dan peluang ekonomi yang inklusif.

# Deskripsi SIP MBER

**SIP MBER** adalah singkatan dari Sistem Informasi Pemberdayaan Masyarakat Berpenghasilan Rendah. SIP MBER sendiri adalah platform digital berbasis edukasi dan komunitas yang berfokus pada pemberdayaan masyarakat berpenghasilan rendah sebagai bagian dari upaya mendukung *Sustainable Development Goals (SDG) nomor 16: No Poverty dan nomor 8: Empowerment of low-income communities.* Tujuan utama dari SIP MBER (Sistem Informasi Pemberdayaan Masyarakat Berpenghasilan Rendah) adalah mendorong pemberdayaan masyarakat berpenghasilan rendah melalui akses yang setara terhadap pendidikan, pelatihan keterampilan, serta peluang ekonomi yang inklusif.

# FLOWCHART dan Use Case Diagram

## Flowchart

1. Flowchart Login

![WhatsApp Image 2025-11-02 at 00 05 56_6e9281f6](https://github.com/user-attachments/assets/874a78a6-02b6-4d5f-b583-307995be1510)

2. Flowchart Buat-Akun

<img width="2964" height="433" alt="image" src="https://github.com/user-attachments/assets/1cf74ea5-ea3b-47e8-9a72-86021f0634b6" />

3. Flowchart menu utama pendaftar

<img width="1043" height="882" alt="image" src="https://github.com/user-attachments/assets/1535921a-a191-48b8-8695-1e6c83d4173e" />

4. Flowchart menu utama staff

<img width="771" height="502" alt="image" src="https://github.com/user-attachments/assets/b07ff9cd-b078-45a9-af01-496b874f3386" />

5. Flowchart menu utama admin

<img width="3635" height="2531" alt="image" src="https://github.com/user-attachments/assets/5f2a1019-7ace-45f3-bf12-dab5a7082910" />

### Use Case DIagram

![WhatsApp Image 2025-10-30 at 19 14 05_68fb7dea](https://github.com/user-attachments/assets/ae30b85e-377d-4d5c-9530-07912bb1efbc)


# Fitur SIP MBER

- **Sistem Login**: ebagai titik navigasi ke fungsi-utama, Memfasilitasi pemilihan jalur sesuai peran (Admin/Staff?PendFaftar).

-  **Registrasi**: Digunakan untuk membuat akun baru sebagai Pendaftar. Data pendaftar dikumpulkan untuk berifikasi, lalu diarahkan ke Menu User setelah aktif.

-  **Tampilam pendaftar (yang belum disetujui status verifikasinya)**: Hanya menampilkan akun ada belum diverifikasi, silahkan login kembali setelah akun sudah disetujui verifikasinya, dan tombol untuk keluar.

- **Menu Utama Peserta**: Halaman utama bagi pendaftar yang status verifikasinya telah lidsetujui. peserta dapat melihat dan mengikuti program-program pelatihan yang diminati. peserta juga dapat melihat sertifikatnya apabila status program pelatihan yang diikuti peserta sudah seleai. Dan peserta dapat memperbarui akun.

- **Menu Utama Staff**: Halaman utama untuk staff dapat melihat daftar-daftar peserta dan pelatihan.

- **Menu Utama Admin**: Halaman utama untuk admin yang bertugas untuk mengelola, mengontrol, dan memperhatikan data-data dari pelatihan, Staff, pendaftar dan peserta.

- **Menu Daftar Pelatihan admin**: halaman dimana admin dapat menambahkan, memperbarui, dan menghapus data dari pelatihan.

- **Menu Daftar Peserta Admin**: halaman dimana admin dapat menambahkan, memperbarui, dan menghapus data dari peserta.

- **Menu Daftar Staff Admin**: halaman dimana admin dapat menambahkan, memperbarui, dan menghapus data dari staff.

- **Menu Daftar Pendaftar Admin**: halaman dimana admin menyetujui ataupun menolak status verifikasi dari pendaftar.


# The 5 Pillars of Object Oriented Programming

**Lima pilar utama dalam Pemrograman Berorientasi Objek (Object-Oriented Programming / OOP)** adalah fondasi yang membentuk cara berpikir dan perancangan sistem berbasis objek.

### Encapsulation (Enkapsulasi)

Pilar pertama, **Encapsulation** atau biasa disebut **Enkapsulasi**, berarti membungkus data dan fungsi dalam suatu kesatuan class untuk menjaga keamanan dan mengontrol akses. Atribut juga dibuat private dengan Getter & Setter untuk mengontrol akses data. Contoh:

<img width="841" height="286" alt="image" src="https://github.com/user-attachments/assets/5d1e55fd-b77f-424f-ae82-f313c1d33db9" />

<img width="917" height="575" alt="image" src="https://github.com/user-attachments/assets/6ffd9824-d94e-49a7-a40b-8047c8f80cbf" />

Pada class Pendaftar, encapsulation diterapkan dengan menjadikan atribut NIK, nama_lengkap, email dll bersifat private kemudian diakses melalui method getter dan setter. Hal ini menjaga keamanan data pendaftar serta membuat struktur kode lebih teratur dan mudah dikelola.

## Inheritanse

Inheritance merupakan salah satu pilar utama dalam Pemrograman Berorientasi Objek yang memungkinkan suatu class (child) mewarisi property dan method dari class lain (parent). Inheritance membantu mengurangi penulisan kode secara berulang (mengurangi redundancy kode). Sebuah kelas (superclass) dapat mewariskan property dan method kepada kelas-kelas turunannya (subclass). Artinya, subclass dapat menggunakan kembali property dan method dari superclass, serta dapat menambahkan property dan method baru atau mengubah perilaku yang sudah ada. Contoh:

<img width="928" height="203" alt="image" src="https://github.com/user-attachments/assets/0a76ff86-9f90-4e43-8428-9911a4adb3b5" />

Class StaffPelatihan mewarisi class Staff. Selain itu, class ini memiliki atribut tambahan cuaca yaitu kelolaPelatihan

<img width="408" height="161" alt="image" src="https://github.com/user-attachments/assets/a65e2707-f8d0-4413-b2ad-3705b8365b0b" />

Sama seperti class staffPelatihan, class Peserta juga mewarisi atribut umum dari pendaftar, dan menambahkan atribut untuk peserta yaitu GetIdPeserta, GetProgress dan lain-lain.

## Abstraction

Abstraksi berarti hanya menaruh karakteristik-karakteristik yang diperlukan oleh sebuah kelas tanpa harus menampilkan detail dari karakteristik tersebut. Dalam abstraction menggunakan abstract class yang merukan kelas abtrak digunakan untuk menentukan karakteristik dari sebuah kelas. Abstract class tidak bisa dibuat menjadi obek secara langsung harus diwariskan. contoh:

<img width="539" height="421" alt="image" src="https://github.com/user-attachments/assets/e7969771-b5c9-474d-99c9-b122653dbd22" />

Class PelatihanServis ini menyederhanakan kompleksitas dengan hanya menampilkan fungsi penting, dan menyembunyikan detail cara kerja. Jadi GUI tidak perlu tahu bagaimana query insert dibuat, bagaimana koneksi database dibuka, dan bagaimana error ditangani.

## Polymorphism

Polymorphism, memberi kemampuan objek untuk memiliki banyak bentuk atau perilaku berbeda tergantung konteks penggunaannya. Metode yang sama (create, read, dll) dapat diimplementasikan dengan perilaku berbeda di class lain. Misalnya di kelas 

- contoh gambar

- contoh gambar

## Interface

Interface adalah kelas yang mengimplementasikannya wajib menyediakan semua method yang ada di dalamnya. contoh:

- Contoh Gambar

- contoh ganbar

## Penjelasan Struktur Package

<img width="280" height="496" alt="image" src="https://github.com/user-attachments/assets/286b687f-77ef-4783-bb22-0b66198565fe" />

## 1. Source Packages

Bagian ini berisi seluruh kode utama program. Di dalamnya terdapat beberapa package yang memiliki fungsi berbeda namun saling berkaitan.

- GUI Package ini berisi komponen tampilan antarmuka yang digunakan oleh pengguna. Seluruh halaman seperti menu utama, form login, registrasi, menu admin, dan menu user terdapat di dalam bagian ini.

- META-INF Package ini berisi file xml, yang akan membantu agar HibernateUtil dapat berjalan.

- Model Package ini menyimpan class-class yang mengimplementasikan private-public, dan Setter & Getter. Seperti Admin, Staff, Staff Pelatihan, Pelatihan, Sertifikat, Peserta, dan Pendaftar.

- Service Package ini menyimpan class-class yang merepresentasikan data atau entitas yang ada di dalam database, seperti pelatihanService, pesertaService dan lain-lain.

- Util Package ini berfungsi sebagai penyedia class pendukung atau helper yang membantu proses kerja aplikasi, misalnya pengaturan format, validasi input, atau fungsi tambahan lain yang digunakan di berbagai bagian program.

## 2. Libraries

<img width="372" height="164" alt="image" src="https://github.com/user-attachments/assets/6ec02779-9c15-47bd-9d88-f463039c3597" />

Bagian ini berisi library eksternal (file .jar) yang dibutuhkan agar program dapat berjalan dengan baik, di antaranya:

- hibernate-core yang digunakan untuk menghubungkan objek Java dengan database melalui konsep ORM.

- mysql-connector-j untuk menghubungkan aplikasi dengan database MySQL.

- AbsoluteLayout untuk membantu pengaturan tata letak tampilan antarmuka / GUI.

# Mengimplementasikan ORM

<img width="909" height="507" alt="image" src="https://github.com/user-attachments/assets/799856fa-0461-4cda-9f7a-8f0baf56a504" />

# Library atau Framework yang digunakan

- Hibernate

  Hibernate digunakan sebagai framework ORM untuk menghubungkan class Java dengan tabel pada database sehingga CRUD dapat dilakukan secara otomatis tanpa banyak SQL manual. Dengan Hibernate, data entity seperti Laporan dapat langsung dipetakan ke tabel laporan.

- MYSQL & JDBC Driver

  MySQL digunakan sebagai penyimpanan data aplikasi sedangkan JDBC Driver berfungsi sebagai penghubung antara Java dan MySQL agar query dapat berjalan dengan baik. Kombinasi ini memungkinkan aplikasi menyimpan data-data seperti data staff, admin, pelatihan, pendaftar, dan peserta secara langsung ke database.

- Java Swing

  java Swing digunakan untuk membangun tampilan antarmuka aplikasi desktop seperti form input, tabel data, dan dialog notifikasi agar user dapat berinteraksi dengan mudah.

- JCalendar

  sebuah library eksternal Java yang menyediakan komponen kalender interaktif untuk aplikasi desktop berbasis Java Swing. Fungsinya adalah untuk memudahkan pengguna memilih tanggal langsung dari tampilan kalender, tanpa harus mengetik manual seperti 2025-11-02.

- Java Enum

  Java Enum dipakai untuk data yang memiliki pilihan terbatas seperti status pelatihan sehingga input lebih konsisten dan mudah dikelola.

# Cara Menggunakan Program

## Bagi Pendaftar

### Halaman Utama

![WhatsApp Image 2025-11-02 at 19 59 43_432c4c36](https://github.com/user-attachments/assets/c266f865-26ec-4b90-8127-9f7bd4aa4e50)

Halaman Utama dari program ini yaitu sebagai tempat login juga. digunakan untuk autentikasi pengguna sebelum mengakses program SIP MBER. Pengguna dapat masuk menggunakan NIK atau username dan passwprd, dan jika belum memiliki akun dapat melakukan registrasi melalui menu ‘Buat Akun’.

### Membuat Akun

![WhatsApp Image 2025-11-02 at 19 54 28_2134b98a](https://github.com/user-attachments/assets/469dd808-39b4-4c4d-9131-0ab837a41fd4)

Halaman Buat Akun digunakan untuk proses registrasi pengguna baru pada aplikasi SIP MBER. Pengguna mengisi data pribadi seperti nik, nama, email, alamat, pekerjaan, penghasilan, nomor HP, dan password. Setelah data tervalidasi, sistem menyimpan informasi tersebut ke database agar akun pendaftar dapat melakukan login ke dalam sistem.

## Role Pendaftar

### Login

![WhatsApp Image 2025-11-02 at 19 56 22_c5d70099](https://github.com/user-attachments/assets/4bc621eb-af51-48b3-aa5f-886cf539a48e)

setelah mendaftar, pendaftar tidak bisa langsung login, kevalidan data harus diverifikasi terlebih dahulu oleh admin, setelah terverifikasi baru bisa login.

## Role Peserta

![WhatsApp Image 2025-11-02 at 19 58 24_b489e77b](https://github.com/user-attachments/assets/d0194ea9-2ddc-4758-b939-4adec2fd0537)

Login menggunakan akun yang telah diverifikasi oleh admin

### Tampilan Utama

![WhatsApp Image 2025-11-02 at 20 01 38_8c133a8f](https://github.com/user-attachments/assets/1d53ec33-0c70-4773-bb7f-e606165c225e)

setelah login maka akan tertampil menu utama dari peserta yaitu daftar-daftar nama pelatihan, pendaftaran pelatihan, perbarui akun, dan lihat sertifikat

### Perbarui Akun

![WhatsApp Image 2025-11-02 at 20 02 53_a2410149](https://github.com/user-attachments/assets/0d97866c-5c1a-40f1-ad6a-c0b00682a511)

Untuk menu perbarui akun di SIP MBER, peserta memilih menu perbarui akun, lalu ubah yanng ingin diperbarui baik itu nik, nama lengkap, alamat, penghasilan, pekerjaan, nomor hp, maupun password. Setelah diubah peserta hanya perlu menekan tombol perbarui untuk memperbarui data pribadi.

### Lihat Sertifikat

![WhatsApp Image 2025-11-02 at 20 03 53_373a007c](https://github.com/user-attachments/assets/a710d24d-0a57-41b8-8829-3044be1f9b7e)

Untuk peserta jika ingin melihat sertifikat di SIP MBER, peserta harus mengikuti suatu program pelatihan dan pelatihan itu sudah mencapai 100% Progress, maka sertifikat untuk peserta akan muncul secara otomatis.

![WhatsApp Image 2025-11-02 at 20 06 04_7ddd3937](https://github.com/user-attachments/assets/5b522246-a485-4efe-9bdf-646397dad736)

Informasi sertifikat di SIP MBER berupa; nama pelatihan yang diikuti peserta, nomor sertifikat, skor program, dan tanggal sertifikat terbit.

## Role Staff

![WhatsApp Image 2025-11-02 at 23 33 27_52b1a17d](https://github.com/user-attachments/assets/e42a8cfc-c4fa-40f8-87f4-8d3b1c49ae5c)

login menggunakana akun staff yang terdaftar

### Tampilan utama

![WhatsApp Image 2025-11-02 at 23 38 05_e425e3fd](https://github.com/user-attachments/assets/519470cb-3675-4cd1-ab63-0135b3061a3c)

Di halaman utama staff, staff dapat melihat daftar-daftar Pelatihan dan daftar-daftar peserta. Juga dapat melakukan penilaian kepada peserta yang melakukan pelatihan

### Penilaian

contih gambar

penjelasan

## Role Admin

![WhatsApp Image 2025-11-02 at 23 16 23_88cc5c39](https://github.com/user-attachments/assets/ed667ae4-8b0d-4bd4-abd1-9be4b0ea914a)

Login menggunakan akun Admin yang telah terdaftar dalam sistem

### Tampilan Utama

![WhatsApp Image 2025-11-02 at 23 36 37_4bfea997](https://github.com/user-attachments/assets/e975b52a-9286-453c-a062-d4b4e62be610)

di halaman utama Admin, Admin dapat melihat Daftar Staff, Daftar Peserta, Daftar Pelatihan dan Daftar Pendaftar. Admin juga dapat melakukan Tambah, perbarui, dan menghapus data dari suatu kategori. Dan dapat melakukan verifikasi ke akun peserta.

### Menu Daftar Pelatihan

gambar

Di halaman daftar pelatihan, Admin dapat menambahkan, memperbarui, dan menghapus data pelatihan.

### Menambahkan Pelatihan

![WhatsApp Image 2025-11-02 at 23 19 50_6081c81e](https://github.com/user-attachments/assets/65988fcf-aef8-480d-9ee7-30bcb2e713ca)

Ketika Admin ingin menambahkan pelatihan admin perlu memasukkan ID pelatihan, nama pelatihan, deskripsi pelatihan (opsional), tanggal mulai, tanggal selesai, dan status pelatihan. Ketika Admin menginput tanggal pelatihan, maka tanggal dimulainya pelatihan tidak bisa melangkahi tanggal selesai pelatihan.

![WhatsApp Image 2025-11-02 at 23 19 24_8bada7a8](https://github.com/user-attachments/assets/43a2c6b9-af62-498a-b57c-c6b71893a55c)

### Memperbarui Pelatihan

Ketika Admin ingin melakukan pembaruan data pelatihan, Admin perlu menekan salah satu data pelatihan yang ada di tabel, kemudian data tersebut otomatis muncul di atas tabel, admin hanya perlu mengubah bagian yang ingin diubah. Misalnya, ID pelatihan, nama pelatihan, deskripsi pelatihan, tanggal mulai, tanggal selesai, ataupun status pelatihan.

![WhatsApp Image 2025-11-02 at 23 17 33_bfc7a5fd](https://github.com/user-attachments/assets/2ea45786-9aa3-4fae-8e94-8c0ec1f942d5)

### Menghapus Pelatihan

Ketika Admin ingin menghapus suatu data di pelatihan, Admin hanya perlu menekan salah satu data di tabel pelatihan, kemudian admin menekan tombol hapus yang ada di kanan atas tabel.

![WhatsApp Image 2025-11-02 at 23 18 01_dd020435](https://github.com/user-attachments/assets/0ad4a26f-c408-42ba-8c1d-705ac0487ada)

### Menu Daftar Staff

Contoh Gambar

Di halaman menu daftar staff, admin dapat melihat daftar-daftar staff. Admin juga dapat menambahkan, memperbarui, dan menghapus suatu data staff.

### Menambahkan Staff

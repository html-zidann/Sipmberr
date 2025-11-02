# SIP MBER



## Anggota Kelompok
- Muhammad Sadikin Samir 2409116031
- Muhammad Fachri 2409116017
- Zidan Daffa Ramadhan 2409116056
- Ahmad Qomarul Arifin 2409116114


## Pengenalan SIP MBER
_Platform_ ini dirancang untuk menghadirkan perubahan sosial yang positif melalui teknologi digital dengan tujuan utama meningkatkan kesejahteraan masyarakat berpenghasilan rendah. SIP MBER berfokus pada akses yang mudah terhadap program bantuan, pelatihan keterampilan, dan peluang ekonomi yang inklusif.

## Deskripsi SIP MBER

**SIP MBER** adalah singkatan dari Sistem Informasi Pemberdayaan Masyarakat Berpenghasilan Rendah. SIP MBER sendiri adalah platform digital berbasis edukasi dan komunitas yang berfokus pada pemberdayaan masyarakat berpenghasilan rendah sebagai bagian dari upaya mendukung *Sustainable Development Goals (SDG) nomor 16: No Poverty dan nomor 8: Empowerment of low-income communities.* Tujuan utama dari SIP MBER (Sistem Informasi Pemberdayaan Masyarakat Berpenghasilan Rendah) adalah mendorong pemberdayaan masyarakat berpenghasilan rendah melalui akses yang setara terhadap pendidikan, pelatihan keterampilan, serta peluang ekonomi yang inklusif.

## FLOWCHART dan Use Case Diagram

### Flowchart

1. Flowchart Login

<img width="2444" height="7128" alt="image" src="https://github.com/user-attachments/assets/ca8561b8-5966-4a29-9447-ff28acd0e110" />

2. Flowchart Buat-Akun

<img width="11936" height="1812" alt="image" src="https://github.com/user-attachments/assets/099f96bf-8be6-4e56-8cc3-075f04af0ff4" />

3. Flowchart menu utama pendaftar

   <img width="4252" height="3608" alt="image" src="https://github.com/user-attachments/assets/401314c1-d0de-4095-bfd7-264172f30796" />

4. Flowchart menu utama staff

<img width="3164" height="2088" alt="image" src="https://github.com/user-attachments/assets/75316bad-6624-4ce7-9e99-b7d9d06123c9" />

6. Flowchart menu utama admin



### Use Case DIagram

![WhatsApp Image 2025-10-30 at 19 14 05_68fb7dea](https://github.com/user-attachments/assets/ae30b85e-377d-4d5c-9530-07912bb1efbc)


## Fitur SIP MBER

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


## The 5 Pillars of Object Oriented Programming

**Lima pilar utama dalam Pemrograman Berorientasi Objek (Object-Oriented Programming / OOP)** adalah fondasi yang membentuk cara berpikir dan perancangan sistem berbasis objek.

### Encapsulation (Enkapsulasi)

Pilar pertama, **Encapsulation** atau biasa disebut **Enkapsulasi**, berarti membungkus data dan fungsi dalam suatu kesatuan class untuk menjaga keamanan dan mengontrol akses. Atribut juga dibuat private dengan Getter & Setter untuk mengontrol akses data. Contoh:

<img width="841" height="286" alt="image" src="https://github.com/user-attachments/assets/5d1e55fd-b77f-424f-ae82-f313c1d33db9" />

<img width="917" height="575" alt="image" src="https://github.com/user-attachments/assets/6ffd9824-d94e-49a7-a40b-8047c8f80cbf" />

Pada class Pendaftar, encapsulation diterapkan dengan menjadikan atribut NIK, nama_lengkap, email dll bersifat private kemudian diakses melalui method getter dan setter. Hal ini menjaga keamanan data pendaftar serta membuat struktur kode lebih teratur dan mudah dikelola.

### Inheritanse

Inheritance merupakan salah satu pilar utama dalam Pemrograman Berorientasi Objek yang memungkinkan suatu class (child) mewarisi property dan method dari class lain (parent). Inheritance membantu mengurangi penulisan kode secara berulang (mengurangi redundancy kode). Sebuah kelas (superclass) dapat mewariskan property dan method kepada kelas-kelas turunannya (subclass). Artinya, subclass dapat menggunakan kembali property dan method dari superclass, serta dapat menambahkan property dan method baru atau mengubah perilaku yang sudah ada. Contoh:

<img width="928" height="203" alt="image" src="https://github.com/user-attachments/assets/0a76ff86-9f90-4e43-8428-9911a4adb3b5" />

Class StaffPelatihan mewarisi class Staff. Selain itu, class ini memiliki atribut tambahan cuaca yaitu kelolaPelatihan

<img width="408" height="161" alt="image" src="https://github.com/user-attachments/assets/a65e2707-f8d0-4413-b2ad-3705b8365b0b" />

Sama seperti class staffPelatihan, class Peserta juga mewarisi atribut umum dari pendaftar, dan menambahkan atribut untuk peserta yaitu GetIdPeserta, GetProgress dan lain-lain.

### Abstraction

Abstraksi berarti hanya menaruh karakteristik-karakteristik yang diperlukan oleh sebuah kelas tanpa harus menampilkan detail dari karakteristik tersebut. Dalam abstraction menggunakan abstract class yang merukan kelas abtrak digunakan untuk menentukan karakteristik dari sebuah kelas. Abstract class tidak bisa dibuat menjadi obek secara langsung harus diwariskan. contoh:



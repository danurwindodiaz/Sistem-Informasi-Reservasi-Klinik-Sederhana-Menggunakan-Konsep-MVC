# Sistem-Informasi-Reservasi-Klinik-Sederhana-Menggunakan-Konsep-MVC
Projek ini merupakan sistem reservasi klinik sederhana menggunakan konsep MVC (Model View Controller) berbasis PHP. Berisi setidak beberapa hal berikut:
- Pengolahn data Reservasi
- Pengolahan data inventaris
- Pengolahan data pasien
- Pengolahan data Pasien

Terdapat satu actor yaitu sebagai petugas

# Cara Install
Cara menginstall aplikasi ini pada komputer Anda (untuk OS Windows) :
- Buat folder baru bernama klinik-rm diretori htdocs (di dalam folder XAMPP)
- Download dan pastekan file ke dalam folder klinik-rm
- Lalu buat database baru pada phpMyAdmin dengan nama db_klinik
- Setelah itu cari dan import file db_klinik.sql ke dalam database db_klinik yang baru dibuat
- Setelah itu coba ketikkan http://localhost:8080/klinik-rm/ pada browser
------------
# Merubah Baseurl
Sebelum mengakses aplikasi pada browser pastikan port yang digunakan dan pastikan baseurl sudah tepat. dapat dipastikan pada file :
> klinik-rm/app/config/config.php

Buka file config,php, lalu cari kode
> define('BASEURL', 'http://localhost:8080/klinik-rm');

Ubah http://localhost:8080/klinik-rm sesuai kebutahan


# Model
Model merupakan bagian yang mengelola dan berhubungan langsung dengan database. Bagian ini terletak pada :
> klinik-rm/app/models/
# View
View merupakan bagian yang akan menyajikan tampilan informasi kepada pengguna :
> klinik-rm/app/views/
# Controller
Controller merupakan bagian yang menghubungkan model dan view dalam setiap proses request dari user :
> klinik-rm/app/controllers/

# Tampilan Sistem
![Image 001](https://user-images.githubusercontent.com/90291471/133005986-eec967e8-bf69-42b5-bcf7-99ba6151d0ad.png) ![Image 002](https://user-images.githubusercontent.com/90291471/133005988-0cd369aa-efad-4668-80ca-bbc2b0bfb561.png) ![Image 003](https://user-images.githubusercontent.com/90291471/133005991-5c11fd07-36b8-459c-b7a1-c42eed7f624a.png) ![Image 004](https://user-images.githubusercontent.com/90291471/133005992-78b45c44-bf6c-40f0-ab40-3f73cdc4bd6e.png) ![Image 005](https://user-images.githubusercontent.com/90291471/133005997-bda7057a-5887-4d96-9ccc-3bb0cc44c603.png)

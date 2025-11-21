RANGKUMAN BAB 1 & BAB 2

BASIS DATA & PENGENALAN MySQL


---

BAB 1 – PENGENALAN BASIS DATA DAN MySQL

1.1 Pengertian Basis Data

Basis data adalah kumpulan informasi yang disimpan secara sistematis sehingga dapat diakses, dikelola, diubah, dan dicari dengan mudah.
Tujuannya adalah untuk mengorganisir data agar penggunaan menjadi lebih efisien dan terstruktur.

Contoh penggunaan basis data:

Sistem perbankan

Sistem akademik kampus

E-commerce

Aplikasi web dan mobile



---

1.2 Sistem Manajemen Basis Data (DBMS)

DBMS adalah perangkat lunak yang mengelola dan mengatur basis data agar dapat digunakan oleh pengguna.

Fungsi DBMS:

Menyimpan data

Memberikan keamanan dan kontrol akses

Memudahkan pencarian dan manipulasi data

Mengatur banyak pengguna (multi-user)

Menangani backup dan pemulihan data


Contoh DBMS:

MySQL / MariaDB

PostgreSQL

Oracle

SQL Server



---

1.3 SQL (Structured Query Language)

SQL adalah bahasa standar yang digunakan untuk mengakses, mengelola, dan memanipulasi data dalam database relasional.

Kategori SQL:

DDL (Data Definition Language) → mengatur struktur database

DML (Data Manipulation Language) → memanipulasi data

DCL (Data Control Language) → keamanan

TCL (Transaction Control Language) → transaksi



---

1.4 MySQL

MySQL adalah sistem manajemen database relasional open-source yang banyak digunakan di aplikasi web.
MySQL pada XAMPP biasanya menggunakan MariaDB, yaitu versi pengembangan dari MySQL yang kompatibel.

Kelebihan MySQL:

Gratis dan open source

Cepat dan ringan

Banyak digunakan di industri

Didukung berbagai bahasa pemrograman



---

1.5 Instalasi MySQL Menggunakan XAMPP

XAMPP adalah paket aplikasi yang terdiri dari:

Apache – Web server

MySQL/MariaDB – Database server

PHP – Bahasa pemrograman web

phpMyAdmin – Antarmuka MySQL berbasis web


Dengan XAMPP, MySQL dapat dijalankan tanpa konfigurasi rumit.
Letak database berbeda sesuai OS:

OS	Lokasi Database	Lokasi PHP

Linux	/opt/lampp/var/mysql/	/opt/lampp/htdocs
Windows	C:\xampp\mysql\data	C:\xampp\htdocs



---

1.6 Masuk dan Keluar dari MySQL via CMD

Masuk ke MySQL:

cd C:\xampp\mysql\bin
mysql -u root -p

Keluar dari MySQL:

\q
bye


---

BAB 2 – DASAR PERINTAH SQL DAN PENGGUNAAN MySQL


---

2.1 Client MySQL

Client MySQL adalah aplikasi untuk berinteraksi dengan server MySQL.

Linux (LAMPP):

/opt/lampp/bin/mysql

Windows (XAMPP):

C:\xampp\mysql\bin\mysql.exe

> Catatan: Semua perintah SQL harus diakhiri tanda titik koma (;).




---

2.2 Tipe Data MySQL

Tipe data diperlukan untuk menentukan jenis data yang dapat disimpan dalam tabel.

Tipe Data	Keterangan	Range / Format

Int	Angka bulat	-2147483648 – 2147483648
Float	Angka desimal	–
Date	Tanggal	YYYY-MM-DD
DateTime	Tanggal & waktu	YYYY-MM-DD HH:MM:SS
Char	String tetap	1–255 karakter
VarChar	String dinamis	1–255 karakter
Blob	Data biner	≤ 65535 karakter
LongBlob	Data biner sangat besar	≤ 4GB



---

2.3 Database Relasional

Database relasional terdiri dari:

Tabel

Field (kolom)

Record (baris)


Pengguna harus membuat database terlebih dahulu sebelum membuat tabel.


---

2.4 Perintah DDL (Data Definition Language)

1. Membuat Database

create database nama_database;

Contoh:

create database praktikum;

2. Melihat Seluruh Database

show databases;

3. Mengakses/Menggunakan Database

use nama_database;

Contoh:

use praktikum;

4. Menghapus Database

drop database nama_database;

Contoh:

drop database praktikum;


---

2.5 Test Akhir (Ringkasan Tugas Praktikum)

1. Cek apakah MySQL dapat dijalankan (login).


2. Buat database dengan nama Prak_NIM.


3. Lakukan perintah SQL berikut:

Membuat database

Menampilkan seluruh database

Mengakses database

Menghapus database



4. Buat perancangan database sesuai arahan asisten.


5. Buat laporan dalam file PrakDB_Bab1-NIM.odt, berisi:

Source code

Screenshot CMD

Tema yang ditentukan



6. Simpan laporan di folder PrakDB-NIM.

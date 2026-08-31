# Web Tiket Bioskop Online

WebTiketBioskopOnline adalah aplikasi web untuk melakukan pemesanan tiket bioskop secara online. Aplikasi ini dibuat untuk mempermudah pengguna dalam melihat film, jadwal tayang, memilih kursi, dan melakukan pemesanan tiket.

## Fitur

* Registrasi dan login pengguna
* Melihat daftar film
* Melihat jadwal tayang
* Memilih kursi bioskop
* Pemesanan tiket
* Melihat riwayat pemesanan
* Manajemen akun pengguna
* Dashboard admin
* CRUD data film
* CRUD jadwal tayang
* Pengelolaan data bioskop dan studio
* Pengelolaan kursi

## Teknologi yang Digunakan

* PHP
* Laravel
* MySQL
* HTML
* CSS
* JavaScript
* Bootstrap

## Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/arundaya24/WebTiketBioskopOnline.git
```

### 2. Masuk ke Folder Project

```bash
cd WebTiketBioskopOnline
```

### 3. Install Dependency

```bash
composer install
```

### 4. Buat File Environment

Salin `.env.example` menjadi `.env`.

```bash
cp .env.example .env
```

Jika menggunakan Windows dan command tersebut tidak bekerja, buat file `.env` secara manual berdasarkan `.env.example`.

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Konfigurasi Database

Buat database MySQL, kemudian sesuaikan konfigurasi pada file `.env`.

```env
DB_DATABASE=web_tiket_bioskop
DB_USERNAME=root
DB_PASSWORD=
```

### 7. Jalankan Migration

```bash
php artisan migrate
```

Jika project memiliki seeder:

```bash
php artisan migrate --seed
```

### 8. Jalankan Server

```bash
php artisan serve
```

Kemudian buka:

```text
http://127.0.0.1:8000
```

## Struktur Project

```text
WebTiketBioskopOnline/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
├── .env.example
├── artisan
├── composer.json
└── README.md
```

## Tujuan Project

Project ini dibuat untuk menerapkan konsep pengembangan aplikasi web menggunakan Laravel, seperti:

* MVC Architecture
* CRUD
* Authentication
* Authorization
* Relational Database
* Laravel Routing
* Laravel Eloquent ORM
* Blade Template
* Database Migration

## Keamanan

File `.env` tidak disertakan dalam repository karena dapat berisi informasi sensitif seperti kredensial database dan application key.

Pastikan file `.env` tercantum dalam `.gitignore`.

## Repository

Repository project:

https://github.com/arundaya24/WebTiketBioskopOnline

## Lisensi

Project ini dibuat untuk keperluan pembelajaran dan pengembangan aplikasi web.

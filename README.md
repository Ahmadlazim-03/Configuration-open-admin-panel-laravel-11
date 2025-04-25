# 🚀 Configuration Open Admin Panel Laravel 11

Deskripsi singkat tentang proyek Anda. Misalnya:  
Sebuah aplikasi web untuk mengelola data pengguna dengan tampilan yang interaktif dan responsif menggunakan Laravel + Livewire.

---

## 📦 Prasyarat

Sebelum memulai, pastikan kamu sudah menginstal:

- [PHP](https://www.php.net/)
- [Composer](https://getcomposer.org/)
- [MySQL / MariaDB](https://www.mysql.com/)
- [Laravel Version 11](https://laravel.com/)

---

## 🛠️ Instalasi

Berikut langkah-langkah untuk menjalankan proyek ini di lokal:

### 1. Clone Repository

```bash
git clone https://github.com/Ahmadlazim-03/Configuration-open-admin-panel-laravel-11.git
cd Configuration-open-admin-panel-laravel-11
cp .env.example .env
```

Buka .env dan sesuaikan sesuai konfigurasi berikut :<br/>

APP_URL=http://localhost -> APP_URL=http://127.0.0.1:8000<br/>
DB_CONNECTION=mysql<br/>
DB_HOST=127.0.0.1<br/>
DB_PORT=3306<br/>
DB_DATABASE=your_data_base<br/>
DB_USERNAME=your_username<br/>
DB_PASSWORD=your_password<br/>

```bash
$ composer install
$ php artisan key:generate
$ php artisan migrate
```

---

## ❗❗❗ Penyesuaian File Vendor pada project laravel anda

<pre>
Configuration-open-admin-panel-laravel-11/
├── app
├── bootstrap
├── config
├── database
├── public
├── resources
├── routes
├── storage
├── tests
├── vendor
    └── open-admin-org 👈
</pre>
    
Temukan folder [ vendor/open-admin-org ] dalam project laravel anda
dan ganti dengan folder yang ada di dalam [ open-admin-org.zip ] yang ada dalam repository yang sudah saya tambahkan

---

## ▶ Jalankan aplikasi

```bash
$ php artisan ser
```
Akses route pada http://127.0.0.1:8000/admin untuk mengakses open admin panel
Login dengan default akun admin :<br/>
username : admin<br/>
password : admin

---


## 📋 Fitur Utama

- ✅ Admin
- ✅ Helpers
- ✅ Media Manager
- ✅ Log Viewer
- ✅ Api Tester
---

## ❌ Hapus Fitur Utama

- ✅ Admin
```bash
$ composer remove open-admin-org/open-admin
```
- ✅ Helpers
```bash
$ composer remove open-admin-ext/helpers
```
- ✅ Media Manager
```bash
$ composer remove open-admin-ext/media-manager
```
- ✅ Log Viewer
```bash
$ composer remove open-admin-ext/log-viewer
```
- ✅ Api Tester
```bash
$ composer remove open-admin-ext/api-tester

```
---




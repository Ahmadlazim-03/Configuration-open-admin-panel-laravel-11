# 🚀 Configuration Open Admin Panel Laravel 11

Deskripsi singkat tentang proyek Anda. Misalnya:  
Sebuah aplikasi web untuk mengelola data pengguna dengan tampilan yang interaktif dan responsif menggunakan Laravel + Livewire.

---

## 📦 Prasyarat

Sebelum memulai, pastikan kamu sudah menginstal:

- [PHP >= 8.0](https://www.php.net/)
- [Composer](https://getcomposer.org/)
- [MySQL / MariaDB](https://www.mysql.com/)
- [Laravel Version 11](https://laravel.com/)

---

## 🛠️ Instalasi

Berikut langkah-langkah untuk menjalankan proyek ini di lokal:

### 1. Clone Repository

```bash
git clone https://github.com/Ahmadlazim-03/Configuration-open-admin-panel-laravel-11.git
cd laravel
cp .env.example .env

Buka .env dan sesuaikan sesuai konfigurasi berikut :
APP_URL=http://localhost -> APP_URL=http://127.0.0.1:8000
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_data_base
DB_USERNAME=your_username
DB_PASSWORD=your_password

composer install
php artisan key:generate
php artisan migrate

Temukan folder [ vendor/open-admin-org ] dalam project laravel anda dan ganti dengan folder yang ada di dalam [ open-admin-org.zip ]

```
---


## 📋 Fitur Utama

- ✅ Admin
```bash
php artisan admin:install
```

- ✅ Helpers
```bash
php artisan admin:import helpers
```

- ✅ Media Manager
```bash
php artisan admin:import media-manager
```

- ✅ Log Viewer
```bash
php artisan admin:import log-viewer
```

- ✅ Api Tester
```bash
php artisan admin:import api-tester
```

---




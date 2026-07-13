# SIPK-DLH ADMIN
Nama : Bara Abiyyi Muslimin
Nim : 23215051
tempat pkl : DLH Kab.Tegal
Teknologi : laravel

Sistem Pelaporan Kegiatan Dinas Lingkungan Hidup — Admin Internal.

Lihat **[INSTALASI.md](INSTALASI.md)** untuk panduan instalasi lengkap.

## Quick Start

```bash
composer install
npm install && npm run build
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan storage:link
php artisan serve
```

**Login:** `/internal-dlh-login`  
**Email:** `admin@dlh.go.id` | **Password:** `admin123`

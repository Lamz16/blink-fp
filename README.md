# BLINK
---
## About
Final project for sutdy digital bussiness

## How to run
1. Clone the repository
2. Copy file `.env.example` to `.env`
3. Generate key using command `php artisan key:generate`
4. Setting file `.env`
   ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=YOUR_DATABASE_NAME
    DB_USERNAME=YOUR_DATABASE_USER
    DB_PASSWORD=YOUR_DATABASE_PASS
   ```
5. Migrate database using command `php artisan migrate`
6. install depedecies
    ```
    composer install
    npm install
    ```
7. Run `php artisan server` and `npm run dev`
8. Access link using web browser

## Dokumentasi
|url|method|keterangan|
|--|--|--|
|`/`|`GET`|Halaman landing page|
|`/contact`|`GET`|Halaman Kontak|
|`/login`|`GET`|Halaman Login|
|`/login`|`POST`|Proses Login|
|`/register`|`GET`|Halaman Register|
|`/register`|`POST`|Proses Register|
|`/logout`|`POST`|Proses Logout|
|`/dashboard`|`GET`|Menampilkan dashboard user|
|`/dashboard`|`POST`|Menyimpan Link yang diinputkan|
|`/{username}`|`GET`|Melihat dafatar url dari user dengan username tertentu|

#### installasi

1. Unduh proyek (atau klon menggunakan GIT)
2. Salin .env.example ke .env dan konfigurasikan kredensial basis data
3. Jalankan `composer install`
4. Tetapkan kunci enkripsi dengan menjalankan `php artisan key:generate`
5. Jalankan migrasi `php artisan migrate --seed`
6. Jalankan seeder data untuk menguji ``` php artisan db:seed AdminSeeder``` dan file seeder db lainnya yang dapat Anda temukan di bawah database/seeders
7. Mulai server lokal dengan menjalankan `php artisan serve`
8. Buka terminal baru dan navigasikan ke direktori akar proyek
Jalankan `npm install`
9. Jalankan `npm run dev` untuk memulai server vite untuk frontend Laravel

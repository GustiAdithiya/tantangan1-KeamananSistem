Aplikasi Sistem Keamanan

Instalation
- composer update
- jika terjadi error
  composer install --ignore-platform-reqs
- php artisan key:generate
- Buat DB sesuai dengan .env (dengan nama "laravel")
- php artisan migrate 
- php artisan db:seed
- php artisan optimize (optional)
- php artisan serve

Task :
validasi login ✓
penambahan hasil pencarian script ✓
penambahan validasi tapi yang salah ✓
encrypt nama gambar, dikasih saat upload tanggal bulan tahun (log)
penambahan salt pada enkripsi ✓
read only button pada saat waktu habis
akses query

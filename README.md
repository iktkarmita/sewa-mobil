Aplikasi Sewa Mobil berbasis web dibangun dengan laravel 5.8 dan Mysql versi PHP 7.1.3

1. Management Pengguna
2. Management Mobil
3. Management Customer
4. Management Transaksi
5. Management List Transaksi Aktif
6. Management History Transaksi
7. Management Setting Aplikasi
8. Management Print Kuitansi Transaksi
9. Management Export Data Transaksi Via Excel

username : Admin,User,Super Admin
email : Admin@google.com, User@google.com, SuperAdmin@google.com
password : karmita
Note : login hanya memakai username dan password

cara menjalankan :
1. install xampp / PHP 7.1.3 dan Composer di Komputer.
2. Ekstrak file menggunakan aplikasi WinRAR.
3. Copy folder SewaMobil, lalu paste ke folder htdocs.
4. Aktifkan Apache dan MySQL pada Xampp.
5. Buka browser, lalu buka alamat localhost/phpMyAdmin.
6. Buat database baru dengan nama sewamobil.
7. pergi ke file cari env.example rename menjadi .env
8. buka .env setting DB_USERNAME=sewamobil 
9. pergi ke cmd ke folder path htdocs cari folder file yang tadi di ekstrak
10. ketik 'php artisan migrate:fresh --seed' (untuk mengcreate database)
11. Buka terminal di dalam project, ketikan 'php artisan serve'
12. Jalankan project dengan ketik http://127.0.0.1:8000/.
13. login dengan username : admin, password : karmita

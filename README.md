# Sistem Informasi Akuntansi-Uang Kas
aplikasi pendataan uang kas dibuat dengan Framework Laravel. Dengan sistem pembayaran kas sekali selama seminggu. Aplikasi ini cocok untuk digunakan untuk di sekolah atau masing-masing kelas.

# Prasyarat
berikut beberapa hal yang perlu diinstall:
- composer
  ```
  https://getcomposer.org
  ```
- PHP 8.2.12
- MySQL ^12
- XAMPP
  ```
  https://www.apachefriends.org
  ```

# Langkah-langkah
- clone repository
  
  HTTPS
  ```
  https://github.com/luviasyiva/Sistem-Uang-Kas.git
  ```
   
  SSH
  ```
   git@github.com:luviasyiva/Sistem-Uang-Kas.git
  ```

- intall seluruh packages yang dibutuhkan
  ```
  composer install
  ```
- siapkan database dan atur file .env sesuai dengan konfigurasi
- jika sudah, migrate seluruh migrasi dan seeding data
  ```
  php artisan migrate --seed
  ```
- generate JWT secret token
  ```
  php artisan jwt:secret
  ```
- ketik perintah dibawah ini untuk menambah cahche baru dari beberapa konfigurasi yang telah diubah
  ```
  php artisan optimaze
  ```
- jalankan local server
  ```
  php artisan serve
  ```
- akses ke halaman
  ```
  http://127.0.0.1:8000
  ```
  

# Flowchart
![flowchart sistem uang kas](https://github.com/luviasyiva/sistem-uang-kas/assets/152132256/f9150f83-6a45-4efe-bb75-f0f22ffff3ed)

# Database
![Screenshot (272)](https://github.com/luviasyiva/sistem-uang-kas/assets/152132256/6cb1ef30-e8ab-4726-9f32-755f172108f4)

# Structure
![Screenshot (271)](https://github.com/luviasyiva/sistem-uang-kas/assets/152132256/a0f36344-9cc5-4407-8a33-c5f47345b9d3)

# Fitur 
- Data Siswa
- Data Kelas
- Data Jurusan
- Data transaksi uang kas
- Data Administrator
- Laporan

 # Tampilan 
 Login
 ![login apk laravel](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/66c99ebb-abee-4c32-b655-5d374de57903)

 Dashboard
 ![dashboard apak laravel](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/e3460347-0072-4a1f-9ceb-ab9dbbbedb31)

 Daftar Pelajar
 ![Screenshot (274)](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/83991ad3-48a2-4802-801e-6dfd38244104)

Daftar Kelas
![Screenshot (275)](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/49660f1d-a08a-4490-941c-f900a3435fac)

 Daftar Jurusan 
 ![Screenshot (276)](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/68f03787-cb94-4c8e-af1d-024d11ffb8bf)

 Daftar Kas
 ![daftar kas apk laravel](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/33ca66ba-210b-4b2e-9889-d9c624dc90f9)
 
Filter kas
![daftar filter kas](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/b724b659-96ad-4911-85d4-07f6cc0900c2)

Daftar Administrator
![Screenshot (279)](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/ff50921c-1d5b-4eec-a8bd-8bcc36598c3f)

Logout 
![Screenshot (280)](https://github.com/luviasyiva/Sistem-Uang-Kas/assets/152132256/deb75714-54d3-4bb0-ba75-3f9dc6860204)


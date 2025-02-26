**📌 Project Name: Web Pariwisata**

**📖 Deskripsi Singkat**

Proyek ini bertujuan untuk menyediakan platform digital yang memudahkan wisatawan dalam mencari informasi tentang destinasi wisata, paket perjalanan, serta layanan pemesanan secara online khususnya destinasi wisata yang ada di Aceh. Web ini akan meningkatkan akses informasi, membantu wisatawan mencari inforamsi destinasi wisata yang ada di aceh, dan memberikan pengalaman yang lebih baik bagi wisatawan.

**👥 Anggota dan Tanggung Jawab**

[M Ziad Akbar] - Backend Developer (Mengembangkan API dan database)

[M Dimas Qhastary] - Frontend Developer (Mendesain tampilan dan UI/UX)

[Muhammad Abiyyu Mizan] - Database Administrator (Mengelola struktur database)

**📌Package yang digunakan**

Backend: PHP, Laravel

Frontend: HTML, CSS, JavaScript, Bootstrap

Database: MySQL

Version Control: Git, GitHub

Deployment: Laravel Forge / Hosting VPS

**📌Tutorial Menggunakan Web Pariwisata**

Clone Repo

git clone 

cd Pariwisata_kece

composer install

npm install

salin .env.example dan ubah namanya menjadi .env, 

DB_CONNECTION=mysql

DB_HOST=127.0.0.1

DB_PORT=3306

DB_DATABASE=

DB_USERNAME=root

DB_PASSWORD=

lanjutkan dengan perintah


php artisan migrate --seed

php artisan storage:link

php artisan key:generate

php artisan serve





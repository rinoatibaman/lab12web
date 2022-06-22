# lab11web_Ci4
# lab11web
- RINO ELJON ATIBAMAN
- 312010006
- TI.20.D1

# LANGKAH KE-1
![2022-06-12](https://user-images.githubusercontent.com/101688124/173205020-4fa0dfd0-c0eb-4c8b-97fc-13f61d7b63d9.png)
![image](https://user-images.githubusercontent.com/101688124/173205024-fe79d3f7-42d7-430c-8767-3df29c0f5387.png)

Menjalankan CLI (Command Line Interface) Codeigniter 4 menyediakan CLI untuk mempermudah proses development. Untuk mengakses CLI buka terminal/command prompt.
![Screenshot (1)](https://user-images.githubusercontent.com/101688124/173205048-5774b704-5a58-47b2-89dc-6817a8825ffe.png)

Arahkan lokasi direktori sesuai dengan direktori kerja project dibuat (xampp/htdocs/lab11_ci/ci4/) Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah: php spark
![image](https://user-images.githubusercontent.com/101688124/173205063-96a46557-dbea-47a3-8a0c-a2886a1ece1c.png)

HOME.PHP
![2022-06-12 (3)](https://user-images.githubusercontent.com/101688124/173205098-174df3b9-b301-4282-9d03-ac0dae995be4.png)

Struktur Direktori Untuk lebih memahami Framework Codeigniter 4 perlu mengetahui struktur direktori dan file yang ada. Buka pada Windows Explorer atau dari Visual Studio Code -> Open Folder.
![2022-06-12 (8)](https://user-images.githubusercontent.com/101688124/173205150-b6f36029-3363-4a6d-9bbb-6b2aa816ba6e.png)

- Routes.php
![2022-06-12 (4)](https://user-images.githubusercontent.com/101688124/173205208-a23548e4-6381-40b5-8a68-2c04a27a4728.png)

-Membuat Route Baru. Tambahkan kode berikut di dalam Routes.php $routes->get('/about', 'Page::about'); $routes->get('/contact', 'Page::contact'); $routes->get('/faqs', 'Page::faqs');
![2022-06-12 (9)](https://user-images.githubusercontent.com/101688124/173205279-4a982ef0-0c2a-4d06-adc5-04ee389faae8.png)

# Membuat Controller
![2022-06-12 (10)](https://user-images.githubusercontent.com/101688124/173205367-f5fac63f-df65-41b5-89e9-1bd770ccb288.png)

Membuat View Selanjutnya adalam membuat view untuk tampilan web agar lebih menarik. Buat file baru dengan nama about.php pada direktori view (app/view/about.php) kemudian isi kodenya seperti berikut.
![2022-06-12 (11)](https://user-images.githubusercontent.com/101688124/173205737-3aa98d79-0c87-454e-b15d-646b50d53284.png)


# Pertemuan 13
- RINO ELJON ATIBAMAN
- 312010006
- PEMOGRAMAN WEB
# Membuat Tabel User
![image](https://user-images.githubusercontent.com/101688124/175068361-026049c1-3d29-4bc2-ba3e-ddc47704312f.png)

![image](https://user-images.githubusercontent.com/101688124/174828171-b05c940a-6094-42cd-a8a7-c7978e060c42.png)
Membuat Model User
Selanjutnya adalah membuat Model untuk memproses data Login. Buat file baru pada
direktori app/Models dengan nama UserModel.php
![2022-06-22 (1)](https://user-images.githubusercontent.com/101688124/175069030-dc67823d-97f1-43d5-a2ef-a9d744d19b37.png)
Membuat Controller User
Buat Controller baru dengan nama User.php pada direktori app/Controllers.
Kemudian tambahkan method index() untuk menampilkan daftar user, dan method
login() untuk proses login.
![2022-06-22 (2)](https://user-images.githubusercontent.com/101688124/175069180-70e9a139-42bb-405f-bd71-ceb8ce0c0fb5.png)
![2022-06-22 (3)](https://user-images.githubusercontent.com/101688124/175069266-81511e77-6107-427c-8a42-fe9cf60e3d1e.png)
Membuat View Login
Buat direktori baru dengan nama user pada direktori app/views, kemudian buat file
baru dengan nama login.php.
![2022-06-22 (4)](https://user-images.githubusercontent.com/101688124/175069356-95812387-ce6b-4bb1-a0c1-8a4b5a01b714.png)
Membuat Database Seeder
Database seeder digunakan untuk membuat data dummy. Untuk keperluan ujicoba modul
login, kita perlu memasukkan data user dan password kedaalam database. Untuk itu buat
database seeder untuk tabel user. Buka CLI, kemudian tulis perintah berikut:
![image](https://user-images.githubusercontent.com/101688124/175072413-feae324d-82cc-4e63-91ea-40d4e89d2e12.png)
Selanjutnya, buka file UserSeeder.php yang berada di lokasi direktori
/app/Database/Seeds/UserSeeder.php kemudian isi dengan kode berikut:
![2022-06-22 (5)](https://user-images.githubusercontent.com/101688124/175076775-3655ae6f-b850-4be4-95f7-09d60ff89804.png)
![image](https://user-images.githubusercontent.com/101688124/175076906-1d4a640e-34b9-4de4-a543-8f9de1e4812c.png)
Uji Coba Login
Selanjutnya buka url http://localhost:8080/user/login seperti berikut:
![2022-06-22 (6)](https://user-images.githubusercontent.com/101688124/175077006-4b0373e6-7187-49ab-a60b-1d1a82116ebb.png)

Menambahkan Auth Filter
Selanjutnya membuat filer untuk halaman admin. Buat file baru dengan nama Auth.php
pada direktori app/Filters.
![2022-06-22 (7)](https://user-images.githubusercontent.com/101688124/175077100-043b63a0-b9e6-4ec6-a600-467ab2437aaf.png)
Selanjutnya buka file app/Config/Filters.php tambahkan kode berikut:
![2022-06-22 (8)](https://user-images.githubusercontent.com/101688124/175077205-5f07446b-0139-4dbd-a569-d99d88be658e.png)


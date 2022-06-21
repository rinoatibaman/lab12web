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

![image](https://user-images.githubusercontent.com/101688124/174828171-b05c940a-6094-42cd-a8a7-c7978e060c42.png)
Konfigurasi dapat dilakukan dengan du acara, yaitu pada file app/config/database.php atau menggunakan file .env. Pada praktikum ini kita menggunakan konfigurasi pada file .env.
![image](https://user-images.githubusercontent.com/101688124/174828564-40fbef19-796a-45e0-962c-e19fc7d0fa5b.png)


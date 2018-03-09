NOW CMS 



Ini adalah project CRUD dengan menggunakan Laravel 5.4 dan ReactJS.

Template yang digunakan adalah template gratis dari creative team , thanks creative team !

dokumentasi template react : https://creativetimofficial.github.io/material-dashboard-react/#/documentation/tutorial
dokumentasi official laravel : cari sendiri ! haha

requirement :
- php versi 5.4 >=
- windows 64 bit (32 bit gagal compile file sass nya )
- xampp (webserver)
- node js

Tutorial instalasi :
- Instalasi laravel
1. Jalankan xampp kamu (webserver), Buat database dengan nama : now_cms
2. Import file sql pada root project pada database now_cms
3. Buka command prompt (cmd) lalu cd ke root project, install laravelnya :
   composer install

4. Copy file .env.example ke file baru .env 
5. isi nama database pada file .env dengan now_cms , isikan user dan password sesuai configurasi database mysql kamu

-- Instalasi frontend (reactjs)
1. Buka command promprt baru
2. Dari folder root project, cd ke public/dev
3. buat file namanya .env

isinya : 
NODE_PATH=./src

4. lalu ketik : npm install
5. Tunggu sampai package selesai di install
6. sekarang jalankan mode development, ketik : npm start
7. perhatikan chrome kamu, akan keluar halaman baru dalam beberapa detik
8. tara !!! selesai

Pada side menu terdapat menu Student, silahkan di explore. sudah dibuat CRUD nya !

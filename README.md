Persyaratan
===========

1. PHP 5.6++
2. NodeJS

Cara Instalasi
==============

1. Clone repository.
`git@github.com:cjzeven/socket.io-guestbook-example.git`

2. Install dependency menggunakan composer.
`composer install`

3. Buat database baru dengan nama `yii2_db`.

4. Import sql file `database.sql` yang berada di folder sql_file

5. Jalankan node server menggunakan `node server.js`

6. Akses `[localhost]/guestbook/index` untuk membuat guestbook baru dan `[localhost]/guestbook/list` untuk melihat list guestbook secara realtime.
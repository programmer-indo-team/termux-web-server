# Yang punya repo gay!


Setup instalasi Web Server Android dengan menggunakan aplikasi Termux yang meliputi paket instalasi PHP, Apache2, MariaDB /MySQL, Composer, PHPMyAdmin, dan mc File Explorer.

Oleh Hadi Khoirudin, S.Kom.

## Cara Instalasinya : 
1. Silahkan buka aplikasi Termux, lalu kemudian jalankan perintah ini :

```
pkg install git -y && cd ~/ && git clone https://github.com/programmer-indo-team/termux-web-server && cd ~/termux-web-server && chmod +x setup && bash setup && cd ~/
```

2. Setelah Termux membuka browser secara otomatis, maka silahkan coba Buka http://localhost:8080.

3. Jika dapat masuk ke dalam tampilan dan tidak ada error maka proses instalasi sudah selesai.

## Cara Menjalankannya : 
1. Silahkan buka aplikasi Termux, lalu kemudian jalankan perintah ini :

```
webserver
```

2. Untuk mengedit file silahkan jalankan perintah berikut ini :

```
cd ~/ && mc
```
3. Untuk menggunakan perintah composer silahkan jalankan perintah composer. Misalnya : 

```
composer create-project --prefer-dist laravel/laravel projectlaravel

```

## Selesai

# Kuis 01

## Setup Wordpress di VM

1. Membuat database wordpress
![Screenshot Membuat Database](img/1.png)
2. Masuk ke direktori ```/var/www/html``` dan download wordpress
![Screenshot Download Wordpress](img/2.png)
3. Extract hasil download
![Screenshot Extract Hasil Download](img/3.png)
![Screenshot Extract Hasil Download](img/4.png)
4. Install php-mysql
![Screenshot Install php-mysql](img/5.png)
5. Edit file ```php.ini``` yang ada di dalam folder ```/etc/php/8.0/apache1```
![Screenshot Edit php.ini](img/6.png)
6. Uncomment atau hapus tanda titik koma (;) yang berada di depan perintah ```extension=mysqli```
![Screenshot Uncomment extension=mysqli](img/7.png)
7. Restart apache service
![Screenshot Restart Apache](img/8.png)
8. Instalasi wordpress melalui browser
![Screenshot Install Wordpress melalui Browser](img/9.png)
9. Setup instalasi wordpress, sesuaikan dengan yang ada di dalam database vm
![Screenshot Setup Instalasi Wordpress](img/10.png)
10. Copy semua baris kode yang ada di browser
![Screenshot Copy Baris Kode](img/11.png)
11. Rename file ```wp-config-sample.php``` yang ada di dalam direktori ```/var/www/html/wordpress/``` menjadi ```wp-config.php```
![Screenshot Rename File wp-config-sample.php](img/12.png)
12. Edit file wp-config.php menggunakan vim
![Screenshot Edit File wp-config.php](img/13.png)
13. Paste baris kode yang sudah di-copy dari browser sebelumnya
![Screenshot Hasil Edit wp-config.php](img/14.png)
14. Kembali ke browser dan melakukan pengisian form informasi sistem wordpress
![Screenshot Form Informasi Wordpress](img/15.png)
15. Proses instalasi wordpress berhasil
![Screenshot Instalasi Wordpress Berhasil](img/16.png)
16. Mencoba login ke dalam sistem wordpress
![Screenshot Login ke dalam Wordpress](img/17.png)
17. Tampilan Dashboard Wordpress
![Screenshot Dashboard Wordpress](img/18.png)
18. Tampilan Wordpress dari sisi guest
![Screenshot Wordpress Role Guest](img/19.png)


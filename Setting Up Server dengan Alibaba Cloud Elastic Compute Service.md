# Setting Up Server
## Cara Install Ulang Server ECS

1. Data center region yang terletak di Indonesia...

    a. Indonesia (Bandung)
    
    b. Indonesia (Surabaya)
    
    **c. Indonesia (Jakarta)**
    
    d. Indonesia (Semarang)
    
2. Mengapa kita perlu untuk install ulang Server ECS...

    a. Untuk mengatasi salah konfigurasi dan terdapat error pada server Alibaba
    
    **b. Untuk mengatasi salah konfigurasi dan terdapat error pada server ECS**
    
    c. Untuk mengatasi salah konfigurasi dan terdapat error pada server web
    
    d. Semua salah

3. Operation System yang digunakan pada proses install ulang...

    a. Red Hat
    
    b. Debian
    
    c. CentOS
    
    **d. Ubuntu**

4. Versi berapa Ubuntu yang digunakan pada proses install ulang...

    a. 15.04 64-bit
    
    b. 21.04 64-bit
    
    c. 18.04 64-bit
    
    **d. 20.04 64-bit**

5. VNC adalah...

    a. Adalah aplikasi yang menyediakan layanan cloud computing
    
    b.  Control yang memungkinkan untuk mengontrol komputer lain melalui aplikasi pihak ketiga
    
    **c. Control yang memungkinkan untuk mengontrol komputer lain melalui koneksi network**
    
    d. Control yang memungkinkan untuk mengontrol jaringan lain melalui koneksi network

## Mengakses Server Melalui SSH

6. Perintah untuk meninstall open SSH server...

    a. Sudo apt download openssh-server
    
    b. Sudo apt install server openssh
    
    c. Sudo apt install openssh
    
    **d. Sudo apt install openssh-server**

7. Perintah untuk mengetahui apakah Open SSH Server terinstall atau sudah berjalan...

    a. Systemctl ssh status
    
    b. System  check-status ssh
    
    **c. Systemctl status ssh**
    
    d. Systemctl status

8. Apa yang dimaksud dengan SSH...

    **a.  Adalah sebagai media transfer data aman yang bisa digunakan secara remote atau dari jarak jauh**
    
    b.  Adalah sebagai media transfer data aman yang bisa digunakan secara jarak dekat
    
    c.  Tools yang digunakan untuk download file melalui SSH
     
    d. Adalah aplikasi open source yang berupa framework dengan model MVC (Model, View, Controller) untuk membangun website dinamis dengan menggunakan PHP

9. Apa singkatan dari CLI...

    a. Compute Line Interface
    
    b. Command Line International
    
    c. Command Line Intercom
    
    **d. Command Line Interface**

10. Perintah untuk terhubung ke dalam server ECS...

    **a. ssh user@Ip_address**
    
    b. user@Ip_address ssh
    
    c. ssh Ip_address@user
    
    d. ssh Ip_address

## Menginstall Web Server Nginx

11. Server web yang digunakan untuk layanan web...

    a. Lighttpd
    
    b. Xitami Web Server
    
    c. Apache Tomcat
    
    **d. Nginx**

12. Perintah untuk install nginx...

    a. Install nginx
    
    b. Sudo apt  nginx
    
    c. Sudo apt download nginx
    
    **d. Sudo apt install nginx**

13. Apa fungsi dari perintah sudo apt update...
    
    a. Untuk melihat daftar paket yang ada di repositori
    
    b. Untuk konfigurasi server
    
    **c. Untuk meng-update daftar paket yang tersedia di repositori sekaligus memeriksa apakah ada pembaruan versi paket yang tersedia untuk diunduh**
    
    d. Semua salah

14. Di bawah ini perintah yang mana untuk mengaktifkan Ufw...

    **a. sudo ufw enable**
    
    b. sudo ufw run
    
    c. sudo ufw start
    
    d. sudo ufw new

15. Perintah untuk melihat status ufw berjalan atau tidak...

    a. sudo ufw stop
    
    b. sudo ufw update
    
    c. sudo ufw enable
    
    **d. sudo ufw status**
    
## Konfigurasi Virtual Host untuk Multi Site Nginx

16. Mkdir digunakan untuk...

    a. Perintah untuk mengubah nama direktori atau folder
    
    b. Perintah untuk berpindah direktori atau folder
    
    c. Perintah untuk membuka folder atau direktori
    
    **d. Perintah untuk membuat direktori atau folder**
 
17. Membuat file index.html dengan menggunakan text editor nano yang disimpan di folder webapp...

    **a. nano  webapp/index.html**
    
    b. nano  index.html
    
    c. nano  webapp=>index.html
    
    d. nano  webapp/index.html

18. Perintah untuk merubah permission dari folder webapp sebagai website direktori agar dapat diakses oleh public...

    a. sudo chown -R www=data:www=data webapp
    
    b. sudo chown webapp -R www-data:www-data
    
    **c. sudo chown -R www-data:www-data webapp**
    
    d. sudo chown -R www-data:www-data

19. Perintah untuk merubah permission dari folder gameapp sebagai website direktori agar dapt diakses oleh public...

     a. sudo chown -R www=data:www=data gameapp
    
    b. sudo chown gameapp -R www-data:www-data
    
    **c. sudo chown -R www-data:www-data gameapp**
    
    d. sudo chown -R www-data:www-data

20. Bagaimana cara untuk melihat isi file config default dari Nginx menggunakan text editor nano yang berada di sites-available...

    a. open nano default
    
    b. default nano
    
    c. nano open default
    
    **d. nano default**
    
## Installasi DBMS MariaDB atau MySQL

21. DBMS adalah...

    a. Adalah suatu sistem atau software yang dirancang khusus untuk mengelola suatu server
    
    **b.  Adalah suatu sistem atau software yang dirancang khusus untuk mengelola suatu database**
    
    c. Adalah suatu sistem atau software yang dirancang khusus untuk mengelola suatu VPS
    
    d. Semua salah

22. Singkatan dari DBMS...

    a. Database Manager System
    
    **b. Database Management System**
    
    c. Data Management System
    
    d. Database Management Software

23. Perintah untuk install MariaDB

    a. sudo apt install -R mariadb-server mariadb-client
    
    b. sudo apt installer mariadb-server mariadb-client
    
    c. sudo apt download mariadb-server mariadb-client
    
    **d. sudo apt install mariadb-server mariadb-client**

24. Perintah untuk melihat status dari MariaDB sudah berjalan atau belum...

    a. status mariadb
    
    b. Systemctl status from mariadb
    
    c. Systemctl run mariadb
    
    **d. Systemctl status mariadb**

25. Berikut yang bukan DBMS...

    a. PostgreSQL
    
    b. SQLite
    
    **c. Microsoft Azure**
    
    d. MongoDB

## Installasi Berbagai Versi PHP GIT dan Composer

26. Singkatan dari VPS...

    **a. Virtual Private Server**
    
    b. Virtual Portable Server
    
    c. Virtual Process Server
    
    d. Virtual Port Server

27. Perintah untuk install Php versi 7.2...

    a. Sudo apt download php7.2
    
    b. Sudo apt php7.2
    
    **c. Sudo apt install php7.2** 
    
    d. install php7.2

28. Perintah untuk install Git...

    a. git install git
    
    b. Sudo apt download git
    
    **c. Sudo apt install git**
    
    d. Sudo apt git

29. Cara mendapatkan installer Composer...

```
    a. php -r "get('https://getcomposer.org/installer', 'composer-setup.php')
    
    b. php -r "download('https://getcomposer.org/installer', 'composer-setup.php')
    
    c. php download installer-setup.php
    
    **d. php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"**

```
30. Perintah untuk menjalankan composer-setup.php...

    a. php artisan composer-setup.php
    
    b. run composer-setup.php
    
    **c. php composer-setup.php**
    
    d. php run composer-setup.php
    
## Deploy Project Laravel Ke Server

31. Perintah untuk clone project dari github...
    
```
    a. php artisan clone <link project github>

    **b. Git clone <link project github>**

    c. clone git <link project github>

    d. clone <link project github>
```

32. Composer update digunakan untuk...

    **a. Meng-update versi seluruh paket dependency di sebuah project/aplikasi**

    b. Fungsi yang berguna untuk menampilkan konten pada halaman

    c. Meng-update record tabel database secara acak untuk digunakan sebagai dummy data atau data sebagai testing

    d. Semua salah

33. Perintah untuk generate random string pada App_key di file .env...

    a. php artisan key generate

    **b. php artisan key:generate**

    c. php key:generate

    d. php key:generate

34. Perintah untuk membuat database MariaDB...

    a. MAKE NEW DATABASE nama_database;

    b. MAKE DATABASE nama_database;

    c. CREATE nama_database;

   **d. CREATE DATABASE nama_database;**

35. Pada laravel, perintah Php artisan migrate digunakan untuk...

    **a. Melakukan migrasi database**

    b. Membuat tabel baru

    c. Membuat model baru

    d. Membuat migration baru

## Mengunggah Project Game Berbasis Web

36. Pada sistem operasi linux, perintah LS digunakan untuk...

    **a. Digunakan untuk melihat atau menampilkan/list isi dari folder/direktori di linux**

    b. Digunakan untuk berpindah direktori

    c. Digunakan untuk membuat direktori baru

    d. Digunakan untuk mengubah akses pada direktori

37. Apa kegunaan dari tools WinSCP...

    **a. Tools yang digunakan untuk upload dan download file melalui protokol ftp atau secure shell (SSH)**

    b. Tools yang digunakan untuk mengakses server

    c. Tools yang digunakan untuk memanajemen database

    d. Semua salah

38. Singkatan dari SSH adalah...

    a. System Shell

    b. Secondary Shell

    c. Shell Secure

    **d. Secure Shell**

39. SSH adalah...

    a. Adalah perintah untuk upload dan download file melalui protokol ftp atau secure shell (SSH)

    b. Digunakan untuk me-manage atau memposisikan apakah pengguna dapat mengakses server tersebut atau tidak

    **c. Adalah protokol transfer yang digunakan untuk mengontrol dan memodifikasi server dari jarak jauh**

    d. Semua salah

40. Tujuan dari perintah chown adalah...

    **a. Digunakan untuk mengubah kepemilikan pada suatu file atau folder kepada user tertentu**

    b. Perintah untuk berpindah direktori atau folder
    
    c. Perintah untuk membuka folder atau direktori
    
    d. Perintah untuk membuat direktori atau folder

## Installasi OS dan Wordpress

41. Wordpress adalah...

    **a. Adalah sebuah aplikasi sumber terbuka (open source) yang sangat populer digunakan sebagai mesin blog (blog engine)**

    b. adalah sebuah aplikasi sumber tertutup (close source) yang sangat populer digunakan sebagai mesin blog (blog engine)

    c. Adalah aplikasi open source yang berupa framework dengan model MVC (Model, View, Controller) untuk membangun website dinamis dengan menggunakan PHP

    d. dalah media penyimpanan file berbasis online atau digital yang mengandalkan koneksi internet untuk akses data

42. Keunggulan dari Wordpress...

    a. Ramah untuk pemula dan ahli

    b. Komunitas besar

    c. Tema beragam

    **d. Semua benar**

43. Singkatan dari VPC adalah...

    a. Virtual Private Compute

    **b. Virtual Private Cloud**

    c. Virtual Private Server

    d. Virtual Private Computer

44. VPC Alibaba Cloud digunakan untuk...

    **a. Membangun lingkungan jaringan yang terisolasi berdasarkan Alibaba Cloud termasuk menyesuaikan rentang alamat IP, segmen jaringan, tabel rute, dan gateway**

    b. Digunakan untuk me-manage atau memposisikan apakah pengguna dapat mengakses server tersebut atau tidak

    c. Membangun lingkungan jaringan yang tidak terisolasi berdasarkan Alibaba Cloud termasuk menyesuaikan rentang alamat IP, segmen jaringan, tabel rute, dan gateway

    d. Semua salah

## Setup SSH & Security Group

45. Perintah untuk melihat apakah Apache2 sudah berjalan...

    a. status apache2

    b. systemctl apache2 status

    **c. systemctl status apache2**

    d. systemctl apache2

46. Kegunaan dari Security Group adalah...

    a. Digunakan untuk menampilkan semua port

    b. Digunakan untuk menampilkan siapa saja yang mengunjungi server

    **c. Digunakan untuk me-manage atau memposisikan apakah pengguna dapat mengakses server tersebut atau tidak**

    d. Digunakan untuk menambah pengguna baru

47. Bagaimana cara untuk masuk ke MySQL Monitor...
    
    a. mysql root

    b. mysql root -p

    c. mysql -u root 

    **d. mysql -u root -p**

48. Perintah untuk agar dapat mengakses dengan jaringan HTTP...

    a. Ufw grant http

    **b. Ufw allow http**

    c. Ufw http allow

    d. Ufw http grant

49. Letak file Wordpress yang sudah didownload...

    **a. var/www/html**

    b. var/www

    c. var/www/wordpress/

    d. var/www/wordpress/html

## Setup Domain & Virtual Host

50. Singkatan dari DNS adalah...

    a. Data Name System

    b. Direction Name System

    c. Domain Name Setting

    **d. Domain Name System**

51. Fungsi untuk apakah DNS...

    a. Mengidentifikasi komputer sebagai titik dalam suatu jaringan

    b. Membuat komputer lebih mudah dalam mengidentifikasi alamat website

    c. Menghafalkan alamat IP dari setiap situs web

    **d. Semua benar**

52. Perintah untuk memindahkan file...

    a. Ls nama_file/direktori_tujuan
    
    b. copy nama_file/direktori_tujuan

    c. switch nama_file/direktori_tujuan

    **d. MV nama_file/direktori_tujuan**

53. Perintah untuk merestart Apache2...

    a. systemctl apache2 restart
    
    b. systemctl reset apache2

    c. restart apache2

    **d. systemctl restart apache2**

54. Apa itu domain...

    a. Adalah aplikasi open source yang berupa framework dengan model MVC (Model, View, Controller) untuk membangun website dinamis dengan menggunakan PHP

    b. Adalah media penyimpanan file berbasis online atau digital yang mengandalkan koneksi internet untuk akses data

    c. Adalah bahasa markah standar untuk dokumen yang dirancang untuk ditampilkan di peramban internet

    **d. Adalah suatu nama unik yang berfungsi untuk mengidentifikasi nama server komputer. Nama domain ini bertujuan untuk mempermudah mengakses ke suatu alamat situs**

## Setup Wordpress

55.  Bagaimana kita merubah header dari blog wordpress...

    a. Menus lalu pilih header image dan cari gambar yang kita pilih untuk header

    b. Colors lalu pilih header image dan cari gambar yang kita pilih untuk header

    **c. Header Media lalu pilih header image dan cari gambar yang kita pilih untuk header**

    d. Post lalu pilih header image dan cari gambar yang kita pilih untuk header

56. Site title digunakan untuk...

    a. Adalah isi dari artikel

    b. Adalah beberapa kata yang menjelaskan mengenai website/blog oleh pembuat blog

    **c. Digunakan sebagai judul situs atau yang biasa digunakan sebagai pengganti logo**

    d. igunakan untuk menampilkan seluruh isi dari post

57. Dibawah ini fungsi Tagline adalah...

    a. Adalah isi dari artikel

    **b. Adalah beberapa kata yang menjelaskan mengenai website/blog oleh pembuat blog**

    c. Digunakan sebagai judul situs atau yang biasa digunakan sebagai pengganti logo

    d. Digunakan untuk menampilkan seluruh isi dari post

58. Kumpulan artikel dalam wordpress dinamakan...

    a. Media

    b. Pages

    **c. Post**

    d. Tags

## Mengunggah Project Codeigniter di ECS menggunakan NGINX

59. Apa yang dimaksud dengan CodeIgniter...

    **a. CodeIgniter adalah aplikasi open source yang berupa framework dengan model MVC (Model, View, Controller) untuk membangun website dinamis dengan menggunakan PHP**

    b. CodeIgniter adalah aplikasi Close source yang berupa framework dengan model MVC (Model, View, Controller) untuk membangun website dinamis dengan menggunakan PHP

    c. CodeIgniter adalah server HTTP dan Proxy dengan kode sumber terbuka yang bisa juga berfungsi sebagai proxy IMAP/POP3

    d. CodeIgniter adalah sebuah perangkat lunak sistem manajemen basis data SQL atau DBMS

60. Perintah SCP digunakan untuk...

    a. Digunakan untuk me-manage atau memposisikan apakah pengguna dapat mengakses server tersebut atau tidak

    **b. Digunakan untuk mentransfer berbagai file antara komputer lokal dalam satu jaringan**

    c.Perintah untuk berpindah direktori atau folder
    
    d. Perintah untuk membuka folder atau direktori

61. Digunakan untuk apa perintah unzip...

    a. Perintah unzip akan membuang semua file dari arsip ZIP

    b. Perintah unzip akan membungkus semua file menjadi arsip ZIP
    
    **c. Perintah unzip akan mengekstrak semua file dari arsip ZIP**

    d. Semua salah

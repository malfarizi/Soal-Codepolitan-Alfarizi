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

    a.
    
    b.
    
    c.
    
    d.

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
    a.
    
    b.
    
    c.
    
    **d. php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"**

```
30. Perintah untuk menjalankan composer-setup.php...

    a. php artisan composer-setup.php
    
    b. run composer-setup.php
    
    **c. php composer-setup.php**
    
    d. php run composer-setup.php
    
## Deploy Project Laravel Ke Server

31.

32.

33.

34.

35.
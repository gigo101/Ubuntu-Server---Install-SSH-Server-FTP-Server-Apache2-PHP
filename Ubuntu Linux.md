
# Install Ubuntu Server 20.04, FTP Server, Apache2 Web Server and PHP

## Linux Commands

### Install Net tools
>sudo apt-get install net-tools

### Restart Ubuntu Server
>shutdown -r 0

### Install VSFTPD Server
>sudo apt-get install vsftpd
>sudo systemctl start vsftpd **To start the FTP Server**
>sudo systemctl enable vsftpd **To enable the FTP Server**

### Install Apache2 Web Server
>sudo apt-get install apache2

### Install Mysql Server
>sudo apt-get install mysql-server
>sudo mysql -uroot  **To login to mysql**

### Install PHP
>sudo apt-get install php libapache2-mod-php php-mysql

### Test if PHP is working
>cd /var/www/html
>sudo nano test.php
>Write your sample php code 
> ip-address-of-your-server/test.php **To test if php is working**


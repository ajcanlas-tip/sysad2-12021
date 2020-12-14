### How to Install Apache, Mysql, and PHP stack on Ubuntu

1. Installing Apache and Updating the Firewall
	- Follow the instruction to install apache and the firewall update
	* sudo apt update
	* sudo apt install apache2
	* sudo ufw app list
	* sudo ufw status

2. Installing MySQL
	- First type this commod on your Ubuntu
		* sudo apt install mysql-server
		* sudo (mysql_secure_installation)
		* after you install it read the instruction carefully)

3. Installing PHP

- Check on your Ubuntu and type this command 'php -v' to check the version of your php
	* if doesn't have a php on your ubuntu type this command
	* sudo apt install php libapache2-mod-php php-mysql
	* after you install it type it again to check the version of your php

4. Creating a virtual host for your website

- Type this command
	* sudo mkdir /var/www/<your_domain>
	* sudo chown -R <$USER:$USER /var/www/your_domain>
	* sudo nano /etc/apache2/sites-available/your_domain.conf

5. Testing PHP Processing on your Web Server

- Type this command
	* nano /var/www/your_domain/info.php

## Reference
Click here [_link_](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04)

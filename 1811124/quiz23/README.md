### How to Install Apache, MySQL, and PHP stack on Ubuntu

## <b> Steps </b> 

1. Installing Apache and Update Firewall 
	a. install your Apache using the command `sudo apt install apache2`
	b. once the installation finish adjust the firewall setting to allow http traffic
	c. check the ufw list using the command `sudo ufw app list`
	d. used the command `sudo ufw allow in "Apache"` it only allow the port 80 
	e. to verify changes used the command `sudo ufw status`.

2. Installing MySQL
	a. Install your MySQL using the command `sudo apt install mysql-server
	b. continue by pressing 'y' and Enter.
	c. start a interactive script by using the command `sudo mysql_secure_installation`
	d. continue by pressing `y` and Enter.

3. Installing PHP
	a. install your PHP using the command `sudo apt install php libapache2-mod-php php-mysql
	b. confirm the Php version using the command `php -v`

4. Creating a virtual host for your website 
	a. create a directory using the command `sudo mkdir /var/ww/your_domain`
	b. assign the ownership of the directory using the command `sudo chown -R $USER:$USER /var/www/domain
	c. open a new configuration file in Apache's site-available using the command `sudo nano /etc/apache2/sites-available/your_domain.conf` and it will create a blank file. 
	d. on blank file copy paste the bare-bones configuration then save it using ctrl+x and then press Y and Enter. 
	e. you can now use `a2ensite` to enable the new virtual hosts use the command `sudo a2ensite your_domain`.
	

5. Testing PHP processing on your web server 
	a. create a new file named info.php using the command `nano /var/www/your_domain/info.php
	b. it will open a blanck file -check in ubuntu the command below- 
	c. to test the script. go to the web browser and access your server's IP address.


<b> Reference </b>

Click this [_link_](https://digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql1-php-lamp-stack-on-ubuntu-20-04)


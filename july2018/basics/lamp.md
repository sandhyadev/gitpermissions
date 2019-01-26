
sudo apt-get update
sudo apt-get install apache2
sudo systemctl restart apache2
sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
sudo systemctl restart apache2
create a file@ /var/www/html/info.php
<?php
phpinfo();
?>




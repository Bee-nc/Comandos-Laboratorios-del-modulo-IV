# Comandos-Laboratorios-del-modulo-IV
sudo apt install apache2 -y
sudo nano /var/www/html/index.html
sudo mkdir -p /var/www/html/miwebsite
sudo nano /var/www/html/miwebsite/index.html
sudo nano /etc/apache2/sites-available/000-default.conf
sudo nano /etc/apache2/sites-available/miwebsite.conf
sudo a2ensite miwebsite.conf
sudo nano /etc/apache2/ports.conf
sudo systemctl restart apache2
sudo nano /etc/hosts
sudo systemctl status apache2
sudo systemctl reload apache2

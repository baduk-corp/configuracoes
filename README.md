# Configuracoes
Todos os arquivos de configurações do servidor

##  Instalaçao:
```
apt-get update
apt-get upgrade
```
``` Apache
apt-get install apache2
```
``` PostgreSQL
apt-get install postgresql
```
``` PHP 7.2
apt install apt-transport-https lsb-release ca-certificates
wget -O /etc/apt/trusted.gpg.d/php.gpg https://packages.sury.org/php/apt.gpg
echo "deb https://packages.sury.org/php/ $(lsb_release -sc) main" > /etc/apt/sources.list.d/php.list
apt update
apt install php7.2
apt search php7.2
apt install php7.2 php7.2-cli php7.2-common php7.2-json php7.2-opcache php7.2-mysql php7.2-zip php7.2-fpm php7.2-mbstring
php -v
systemctl restart apache2
```

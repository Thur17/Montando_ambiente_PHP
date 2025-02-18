# Comando de montagerm de ambiente para PHP.

## Abaixo segue passo a passo de monatgem de ambiente para PHP.

## inicio de instalação

```bash
sudo apt-get install apache2
```
```bash 
sudo apt-get install php8.3
```
```bash 
sudo apt-cache search mysql | grep server
```
```bash 
sudo apt-get install mysql-server-8.0
```
```bash 
sudo mysql_secure_installation
```

## Instruções para instalação do MySQL
```bash
https://phoenixnap.com/kb/install-mysql-ubuntu-22-04
```
```bash
https://dev.mysql.com/downloads/workbench/
```
```bash
sudo systemctl restart mysql
```

```bash
mysql -u root
```
```bash
UPDATE mysql.user SET authentication_string=null WHERE User='root';
```
```bash
exit
```
```bash
sudo systemctl restart mysql
```
```bash
mysql -u root
```
```bash
ALTER USER 'root'@'localhost' IDENTIFIED WITH caching_sha2_password BY 'password';
```
## Finalização da instalação
```bash
sudo apt-get install php8.3-mysql
```
```bash
sudo apt-get install php8.3-mbstring
```
```bash
sudo apt-get install php8.3-xml
```
```bash
sudo apt-get install php8.3-zip
```
```bash
sudo apt-get install php8.3-imagick
```

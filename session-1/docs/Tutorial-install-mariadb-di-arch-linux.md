# TUTORIAL INSTALL MARIADB DI ARCH
## 1. Masuk ke terminal
masukkan
```
sudo pacman -S mariadb
```
jika sudah selesai installasi masukkan command
```
sudo mariadb-install-db --user=mysql --basedir=/usr --datadir=/var/lib/mysql
```
lalu masukkan command
```
sudo systemctl enable mariadb
```
lalu masukkan command
```
sudo systemctl start mariadb
```
lalu masukkan command
```
systemctl status mongod
```
jika tampilanya seperti ini maka proses installasi sudah selesai

<img width="1366" height="736" alt="install mariadb3" src="https://github.com/user-attachments/assets/de2f0680-38e1-482d-a4a0-8c0eb3b25cc4" />

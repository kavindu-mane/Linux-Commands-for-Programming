# Linux Commands for Programming

## Myslq
* install 
	```
	sudo apt install mysql-server
	sudo systemctl status mysql
	```
	_Mrthod - 1_
	```
	sudo mysql
	```
	
	_Mrthod - 2_
	```
	sudo mysql --defaults-file=/etc/mysql/debian.cnf
	```
	
	in mysql terminal enter,
	```
	ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'newpassword'
	exit
	```
	
	```
	sudo mysql_secure_installation
	```
	

* uninstall
	```
	sudo apt-get remove --purge mysql-server mysql-client mysql-common
	```

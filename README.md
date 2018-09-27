# Installing-MYSQL-on-Ubuntu
Detailed steps of installing mysql
Installing MYSQL ON UBUNTU SERVER VIA TERMINAL

Steps I took in installing Mysql on Ubuntu server

The first step was to open MYSQL download page. I scrolled till the end of the page and clicked on download. I copied the file location and went to Ubuntu terminal.
I went to cd /tmp directory and downloaded the file using wget
I was able to confirm that the file is present by using the ls command.
The file name was listed  as mysql-apt-config_0.8.10-1_all.deb

The next step was to add MYSQ to my repository using sudo dpkg-I mysql-apt-config*
After doing this, a screen came up and asked me to choose the  version of mysql and I chose the default option and clicked ok
The next step was to install mysql using   sudo apt install mysql-server.
 I approved it and pressed y and clicked enter. The software gets installed and I was asked to create a root password which I did. Mysql has been installed and running but I needed to secure the software using mysql_secure_installation
I was then asked for my root password which is typed. I was able to test if MYSQL is running by using mysqladmin -u root -p version


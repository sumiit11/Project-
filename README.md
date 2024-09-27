apt-get update
apt-get install apache2 -y
apt-get install mysql-client -y
pscp -i sumit-nv.ppk "index.php" ubuntu@ip adress :/home/ubuntu
ls
show index.php
cd /var/www/html
ls
rm -r index.html
ls
mv index.php /var/www/html
ls
cd /var/www/html
ls
add repository---------------
add-apt-repository -y ppa:ondrej/php
apt install php5.6 php5.6-mysqli -y
ls
nano index.php
create a RDS
nano index.php
server name ="rds endpoint"
username = "sumit"
password = sumit12345
db = project-new
:wq
connect to databases
mysql -n paste endpoint data -u sumit -psumit12345
show databases;
use project-new;
show tables;
create a table----------------
create table data (firstname varchar(20),email varchar (20));
name :sumit
email: kumarsumit34066@gmail.com
new record save---------------------------
select * from table;
go to create AMI-------------------------------
After create Autoscaling----------------------------
After create launch Configuration----------------------------
Create target group---------------------------------
Attach to a new load balancer----------------------------------
Then a create a databses easily..............................# Project-
Deploying a multitier website in ec2

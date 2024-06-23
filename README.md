Website
Steps to host website on AWS :

create a aws EC@ instance of REDHAT linux Distribution
connect to instance using CLI such as MobaXterm
commands :
1. sudo su -
2.  yum update -y
3.  yum install git -y
4.  yum install httpd
5.  git clone "git-repo-link" master 
6.  cd master 
7.  copy the files into default directory /var/www/html/ 
8.  systemctl start httpd
copy your aws instance public ip onto your browser

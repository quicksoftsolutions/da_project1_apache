**INTRODUCTION**
The task is about the installation of the LAMP stack on The AWS SERVER LAMP (Linux, Apache, MySQL, PHP or Python, or Perl)

1. I followed the Process to install EC2 instance on the AWS Cloud hosting , creating an account with Amazon Web Services and using putty I was able to logging into the Ubuntu machine console. 


1. I updated the Server and Installed Apache2 on it  using **sudo apt install apache2** 


1.  I install Mysql server Using **sudo apt install mysql-server** I configured the Database and user for the Database using the instruction


1. I install PHP **sudo apt install php libapache2-mod-php php-mysql**  


1. I created a virtual Host and pasted the virtual host code provided 


1. I enable PHP on the website , I changed the other of index file loading  using **sudo vim /etc/apache2/mods-enabled/dir.conf** reloade Apache with 
   **sudo systemctl reload apache2** I created a New index.php enter the php.info to view the Php version which is 8.1.2
   
   
1. I edit the security group Inbound rule to allow the website access from http and allow SSH


1. I removed the content of the file and Added a custome website content and was able to deploy a 1 page website on the server.

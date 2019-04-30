# SS
Software Security Assignment 2 
Deploy this demo to Your Computer 1. Prerequisite - XAMPP or any other web server install in your computer to run php application. - Text editor to edit code snippet (Notepad, Sublime text). 
 
How to: install XAMPP on your PC and run this demo 
 
XAMPP – acronym for Cross-Platform, Apache, MySQL, PHP and Perl – is a widely adopted Apache distribution used to locally host and test websites. 
Download and Install Visual Studio 2008 redistributable package because XAMPP will need this to run properly. 
Download XAMPP It’s available as a unique installation package for Windows and other platforms. You can download the package from the official site. 
XAMPP is a powerful tool in the hands of a web developer. 
The installation procedure is quite simple, just double-click on the installer and follow these steps. 
If you have UAC enabled – and we hope so – remember to install XAMPP inside the folder C:\xampp. Anyway the installer suggest to do so: Download from official site 
 
 
1. Run download file by double click on it or just enter on this file. 
 
2. Follow below step 
 
 

 
 
 

 
 
 

 
 
 
- Start apache and MySQL (for database) to run your php application. 

 
- On start if you get this error then follow below steps to successfully run your web server to run php application. 
 
 
 

 
 
 
- Server started successfully now open the browser and open any one of below url o http://localhost o http://127.0.0.1:8080/ (8080 is your port number user in case of you changed default). This shows you below screen 

 
- Select your prefer language. 3. Now time to run php application. - Download this repo as a zip - Unzip the code and copy paste it to C:\xampp\htdocs 
 
- Run this code by project folder name in browser. o http://localhost/server_side_token_validation  o http://localhost/cookie_token_validation  - For Server Side Token Validation you need to create database and import database from server_side_token_validation > DB > database.sql - Follow this step to import database o First start phpmyadmin. phpMyAdmin is a free software tool written in PHP, intended to handle the administration of MySQL over the Web. o Open http://localhost/phpmyadmin or http://127.0.0.1:8080/phpmyadmin 
 
 
 
Create new database : enter name and click create button 
 
 
 
 
 
                                  Click import to import database one you have  
                     
       Choose db file and click go button below 
 

 
 
- Now edit the connection file in /server_side_token_validation/connection.php 
 
- Reload previews run URL to check token functionality. 


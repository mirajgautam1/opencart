OpenCart is a free open-source e-commerce platform. This project includes the manual testing of this application.

REQUIREMENTS
These extensions must be enabled for OpenCart to install properly on the web server.
● PHP 5.4
● JavaScript
● Database (MySQL suggested)
● Web Server (Apache suggested)

INSTALLATION
To install and run opencart on windows, following steps need to be performed:
1. Download Apache server from https://www.apachefriends.org/download.html
2. Download Opencart from https://www.opencart.com/index.php?route=cms/download
3. Extract the downloaded zip opencart file and copy it to the downloaded xampp folder in C drive.
4. Rename files
   Go to C:\xampp\htdocs\opencart\upload
   Rename file config-dist.php -> config.php
   Again,open the admin folder and rename config-dist.php -> config.php
5. Connect to the database and create DB
   DB Access URL: http://localhost/phpmyadmin/
   Create new database ‘openshop’
6. Open the site : http://localhost/opencart
7. Provide database connection details
8. Go to application URL
   Front End store URL : http://localhost/opencart/upload
   Backend Admin URL : http://localhost/opencart/upload/admin
9. To login to administration application
    Username: admin
    Password: admin

   
Below is the description of all the included documents of this opencart manual testing repository.

Functional Requirement Specification: This document explains what a system or software is supposed to from a user or business perspective.
Test Plan: It is a structured document which explains how testing will be carried out for a project.
Test Scenarios: It includes high level description of what you want to test in an application.
Test Cases: They are detailed step-by-step instructions used to verify whether a specific feature of a software application is working correctly or not.
Bug Report: This document contains the description of all the bugs found after the execution of test cases by a tester.
Requirement Traceability Matrix: A Requirement Traceability Matrix is a document used in software testing to map and track requirements with their corresponding test cases.






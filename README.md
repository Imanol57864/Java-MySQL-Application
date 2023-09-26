# Java-MySQL-Application (my-take)
This project is an example of a Java Application which requires MySQL and NetBeans to work. Its very simple, just an interface with some backend.
One key aspect of this project is the implementation of a database into an interface; the data is saved while the user can close and open the program at any time.
If you want to duplicate this project, follow the steps below.

<img width="570" alt="Interfaz 1" src="https://github.com/Imanol57864/Java-MySQL-Application/assets/67908214/b752f5da-5c4b-413a-937a-1df8bfb11150">

<img width="941" alt="Table1" src="https://github.com/Imanol57864/Java-MySQL-Application/assets/67908214/ca8e2099-b6bf-44ec-836b-e53c17e1eaac">

<img width="960" alt="Input1" src="https://github.com/Imanol57864/Java-MySQL-Application/assets/67908214/e2630714-f97e-470d-a897-b37fce810ee2">

## Download these
JDK 17:
https://www.oracle.com/mx/java/technologies/downloads/#jdk17-windows

Neatbeans IDE 17: 
https://netbeans.apache.org/download/nb17/index.html

XAMPP:
https://blog.containerize.com/how-to-setup-xampp-and-phpmyadmin-as-localhost-on-windows/

Java-MySQL Connector Jar:
http://www.java2s.com/ref/jar/download-mysqlconnectorjava5147jar-file.html#google_vignette

The EmployerInformation zip from this project:
https://github.com/Imanol57864/Java-MySQL-Application/blob/main/EmployerInformation.zip

The DB template from this project:
https://github.com/Imanol57864/Java-MySQL-Application/blob/main/records.sql

## Setup
1st - Install JDK 17.
2nd - Install NetBeans IDE 17.
3rd - Install XAMPP.
4th - Import the project  "EmployerInformation.zip" into NetBeans.
5th - Open XAMPP and Start Apache and MySQL. (Got Problems? Go to XAMPP Setup down below).
6th - Click on Admin from MySQL.
7th - Create a new database and import the DB template.
8th - In NetBeans, Go into EmployeeInformation -> Source Packages -> employerinformation -> Interfaz.java".
9th - Build and clean that file, then, run it.
Now start playing with it. Try adding some information or click on the ID from the table and the click on delete to remove some information.


## XAMPP Setup 
1. Start "Apache" y "MySQL".
2. Click on Configure from Apache, then "phpMyAdmin config.inc.php".
3. Go to " /*Bind to the localhost ipv4 address and tcp */ ".
4. Change 'host' ip address for 'localhost:*PORT*'. (*PORT* = the port that shows up in XAMPP from MySQL)
(Extra help: https://www.youtube.com/watch?v=2mHJTv3gyDE)

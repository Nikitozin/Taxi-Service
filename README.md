# Taxi Service

![Image of Taxi](https://taxi-vse.ks.ua/images/taxi.png)

The goal of this project is to create simple taxi service for drivers with authentication system. You can register new drivers, add new cars, add manufacturer what made it. Add cars to your drivers.  
In project used N-tier architecture with:
* DB layer
* DAO layer
* Service layer
* Controllers layer

## Technologies used:
* Apache Tomcat (version 9.0.46)
* MySQL (version 8.0.24)
* JDBC
* JSP
* Servlet
* JSTL
* Logger
* Maven
* Maven Checkstyle Plugin

## Setup:
1. To run the project on your computer, clone this project into your local folder and open the project in an IDE. 
2. Install MySQL and MySQL Workbench, to configure MySQL you can use the script from resources/init_db.sql.
3. Install and configure Local Tomcat Server.
4. Change parameters in taxi/util/ConnectionUtil.java:
* URL to your database
* Your Login to database
* Your password to database
5. Create new driver by clicking "Sign up" button.


# :oncoming_taxi:taxi-service

## 📑Project description:
A simple web-application that supports authentication and registration.
It is based on 3 models: `Manufacturer`, `Car` and `Driver`, on which you can perform basic `CRUD` operations.
They are interconnected by the following relationships:
+ `Car` -> `Manufacturer` : Every `Car` is associated with a `Manufacturer`;
+ `Driver` <--> `Car`: Every `Driver` is associated with a `Car` and vice versa.

App follows a three-tier architecture by separating presentation, application, and data tiers:
+ `Controller`: handles incoming requests by providing an interface to interact with a user, invokes services to process requests, and displays a response;
+ `Service`: handles the business logic of the app;
+ `DAO`: manages and stores the information given by the `Service` layer.

## ✅Features:
+ Register as a driver;
+ Log in as a driver;
+ Create/delete a `Manufacturer`;
+ Create/delete a `Car`;
+ Create/delete a `Driver`'
+ Link `Driver` to `Car`'
+ Display all the `Manufactures`;
+ Display all the `Cars` with all the linked `Drivers`;
+ Display all the `Cars` linked with the current authenticated `Driver`;
+ Display all the `Drivers`.

## :gear:Technologies:
+ JDK 11
+ Maven 3.8.6
+ JDBC
+ MySQL 8.0.22
+ Tomcat 9.0.50
+ Servlet 4.0.1
+ JSP
+ JSTL 1.2

## :arrow_forward:Hot to use:
1) Clone the project;
2) Set up DB by using the `resources/init_db.sql` script;
3) Edit `ConnectionUtil` class with valid path and credentials;
4) Configure Tomcat and run the app;

:green_circle: **App is also available by the [link](http://app-env-3.eba-ukv8akpm.eu-north-1.elasticbeanstalk.com/)!**

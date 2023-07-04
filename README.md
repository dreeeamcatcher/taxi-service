# taxi-service🚕

## 📑Project description:
A simple web-application that supports authentication and registration.
It is based on 3 models: `Manufacturer`, `Car` and `Driver`, on which you can perform basic `CRUD` operations.
They are interconnected by the following relationships:
+ `Car` -> `Manufacturer` : Every `Car` is associated with a `Manufacturer`;
+ `Driver` <--> `Car`: Every `Driver` is associated with a `Car` and vice versa.

:green_circle: **App is available by the [link](http://app-env-3.eba-ukv8akpm.eu-north-1.elasticbeanstalk.com/)!**

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

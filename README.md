# WHProj495
Warehouse Inventory Management System Capstone Project

## Prerequisites
```
1. JDK 10 or JRE 8
2. SQL Database

```
## Installation
```
Download Inventory Manager.jar
```
## Usage

Once the executable has been downloaded and run the program will begin searching for the SQL server. 
By default it will be expecting to connect to a server on localhost at port 1521 wither username system and password 123456. 
If it does not find a server that meets these requirements it will give the user the opportunity to enter in their credentials as shown below:

![alt text](images//login.PNG)

If an appropriate login is not entered then the user will be met with the following error:

![alt text](images//could_not_connect.PNG)

Once the user has logged in properly they will be taken the the main display of the application. This display will show the various items that are currently available in inventory.

![alt text](images//Main.PNG)

# Hotel_Mangement_System
This is a Project I developed a hotel management system using core java and MySQL as database management system. This implemented project provides the basic functionality of hotel management system. 

## Setup
* Clone the github repo into local computer
* First create a temporary database in MySQL
  ```shell
        CREATE DATABASE hotel_database;
  ```
* Create a table using
  ```shell
         CREATE TABLE reservations(
         reservation_id INT AUTO_INCREMENT PRIMARY KEY,
         guest_name varchar(255) NOT NULL,
         room_number int NOT NULL,
         contact_number varchar(10) NOT NULL,
         reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
         );
  ```
* open the src file in any local IDE then change the url, username, password according to your personal system
* Then run the App.java file

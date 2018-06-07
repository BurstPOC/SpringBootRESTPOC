# SpringBootRESTPOC
This is a sample Spring Boot project. Spring Boot has been used to expose REST Endpoints. 
This application has a connectivity to mysql database. 

This project uses following technologies:

1. Spring Boot v1.5.9
2. Maven
3. MySql

# License
This project is licensed under the MIT License. 

#Deployment
One can simply import this project into Spring Tool Suite IDE and run it. 
Make sure it has changes according to your database details. 


#Mysql query
CREATE TABLE regions (
`id` INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
region_id INT(3) , country_names varchar(25) not null
)


ALTER TABLE regions ADD region_names varchar(25) not null;

# Author
Kailash Nirmal

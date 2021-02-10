# fullstackteam-poc-for-employee
A full stack web application for individual who is looking for designing a web app which uses Springboot as a backend framework and React.js as frontend.
This repository is basically divided into two parts; frontend and backend.

# It covers the below items:
* How to build React apps?
* How to build Spring Boot apps?
* How to encapsulate the backend to the frontend?

# Prerequisits 
* maven, npm and java, mysql. 

# To run the application, run the following commands from the console.

* The default port number for running react.js application http://localhost:3000 
* springboot it is http://localhost:8080
* To view the database, you can click on http://localhost:8080/view


# Frontend:
* npm install
* npm start

# Backend: 
* mvn clean install
* To skip running the tests for a particular project, set the maven.test.skip property to true
* mvn clean install -Dmaven skip.test=true
* java -jar target/springboot-0.0.1-SNAPSHOT.jar

# mysql:
* command to take the sql dump
  mysqldump -u [user] -p [database_1] [database_2] [database_etc] > [filename].sql
* command to restore dump 
  mysql -u [user] -p [database_name] < [filename].sql
  

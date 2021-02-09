# fullstackteam-poc-for-employee
A full stack web application for anyone who is looking for designing a web app which uses Springboot as a backend framework and React.js as frontend.
This repository is basically divided into two parts; frontend and backend.

We will be learning:
1.	How to build React apps?
2.	How to build Spring Boot apps?
3.	How to encapsulate the backend to the frontend?

You need maven, npm and JAVA pre-installed, which most probably you'll already have.  To run the application, run the following commands from the console.

The default port number for running react.js application http://localhost:3000 and for springboot it is http://localhost:8080
To view the database, you can click on http://localhost:8080/view

Frontend:
npm install
npm start

Backend: 
mvn clean install
mvn -Dmaven skip.test=true install (to skip tests)
java -jar target/springboot-0.0.1-SNAPSHOT.jar

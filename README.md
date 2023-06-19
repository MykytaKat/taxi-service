# Taxi-service
This is web application to show simple CRUD operations,
authentication, and registration using MySQL and servlets, without any
frameworks.

### Functionality 

 - register a driver
 - log in/ log out
 - create/read/update a driver
 - create/read/update a car
 - create/read/update a manufacturer
 - show all drivers
 - show all cars
 - show all manufacturers

### Project structure

- DAO (Data Access Object) - receives requests from the service, transfers them to the database, and executes all SQL queries.
- Service - receives requests from the controller, transmits them to the DAO level, and executes all business logic.
- Controller - receives requests from the user, transmits them to the service layer, and returns jsp pages in response.

### Technologies used: 

- Maven
- Java programming language (JDK 1.8)
- JDBC
- Java Servlet
- JSP and CSS
- Tomcat 9.0.75
- MySQL 8.0
- Servlet API

### Instructions for launching the project

1. Clone this project from GitHub
2. Install Apache Tomcat v.9
3. You need to create a database using a local MySQL or a remote database. You need to execute the schema that can be found in the init_db.sql file.
4. Fill in the appropriate fields in ConnectionUtil
5. Set up the configuration for tomcat 

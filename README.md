# taxi-service

Typing SVG
Project structure:
The project has an N-Tier Architecture

DAO - data access objects - all the work with the database takes place at this stage(CRUD methods)
Service - all business logic takes place at the service level
Controller - information display
Features:
registration
authentication
create, update and remove all models
display list of all manufacturers, cars, drivers
Frameworks:
MySQL
Java Web
Instructions for launching the project:
Fork my repository
git clone <your link>
Edit ConnectionUtil.class - set the necessary parameters
private static final String URL = "URL";
private static final String USERNAME = "USERNAME";
private static final String PASSWORD = "PASSWORD";
private static final String JDBC_DRIVER = "JDBC_DRIVER";
Create the necessary tables in your database from the file init_db.sql
Install Tomcat
Add Tomcat server to configuration
Run project
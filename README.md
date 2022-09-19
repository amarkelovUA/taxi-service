# taxi-service :taxi:

### :rainbow: ABOUT
This simple web-app allows you to store information about cars and drivers.
It also provides an opportunity to add appropriate drivers to each car.
And to view the current state of these connections.

### :dart: FEATURES
+ registration
+ authentication
+ create, update and remove all models
+ display list off all cars, drivers, manufacturers

### :hammer: TECHNOLOGIES AND FRAMEWORKS
+ Java WEB (web servlets)
+ JDBC
+ MySQL
+ Dependency Injection

### :vertical_traffic_light: PROJECT STRUCTURE
The project has an N-Tier Architecture.
+ DAO 
> all the work with the database takes place at this stage(CRUD methods).
+ Service
> all business logic takes place at the service level
+ Controller
> interacts with the user

### :eyes: INSTRUCTIONS FOR LAUNCHING THE PROJECT:
1. Fork this repository
2. Clone the repository to your PC
3. Create the necessary tables in your database from the file init_db.sql
4. Edit ConnectionUtil.class - set the necessary parameters:
~~~java
    private static final String URL = "URL";
    private static final String USERNAME = "USER NAME";
    private static final String PASSWORD = "PASSWORD";
    private static final String JDBC_DRIVER = "JDBC DRIVER";
~~~
5. Install Tomcat (9.0.50)
6. Add Tomcat server to configuration
7. Run project

[This app is deployed on Heroku.] (https://mighty-beyond-04392.herokuapp.com/)
(uses www.remotemysql.com)

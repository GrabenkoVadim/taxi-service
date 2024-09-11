# Taxi Service

<a name="Overview"></a>
## Overview
Taxi Service is the simple analog of taxi application where you can perform basic operations. The project is built using a multi-tier architecture to ensure separation of concerns and scalability, making it a simple yet effective solution for managing taxi services.
<a name="Use-cases"></a>
## Use cases

* Log in / Log out
* Registration
* Create a new car / delete a car
* Create a manufacturer / delete a manufacturer
* Create a new driver / delete a driver
* Add a driver to the car
* Show all drivers
* Show all manufacturers
* Show all cars
* Show all cars for current user

<a name="Used-Technologies"></a>
## Used Technologies

* Java 11
* Custom Injector
* Apache Tomcat (v9.0.50)
* MySQL
* JDBC
* HttpServlet and HttpFilter
* HTML, CSS, JSP, JSTL
* Maven

<a name="Project-structure"></a>
## Project structure
Project implemented refers to an n-tier structure and has three layers:

1. DAO layer
1. Service layer
1. Controllers layer

<a name="Application-startup"></a>
## How to run this project

1. Configure Apache Tomcat (v9.0.50) for your IDE
2. Install MySQL
3. Run the script from resources/init_db_my.sql Warning! if you already have a DB named "taxi", this script will delete it and create a new empty DB with the same name.
4. In src/main/java/taxi/util/ConnectionUtil replace "YOUR URL TO DATA BASE", "YOUR USERNAME", "YOUR PASSWORD" stubs with your properties.
5. Configure TomCat Local server (Add New Configuration -> TomCat -> Local -> Fix -> taxi-service:war exploded -> OK)
6. Run project!

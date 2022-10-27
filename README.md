# :movie_camera: Cinema-app :movie_camera:
![cinema-hall](https://english-skype.net/wp-content/uploads/2019/07/Teaser-Cinema-1200-500.jpg)
## :clipboard: Description :clipboard:
The goal of the project is to create a cinema application with a registration, authorization and authentication system that supports CRUD operations with tickets, films, shopping carts, orders, movie sessions and movie theaters

## :star2: Features :star2:
* User registration, admin role setting, otherwise for each user (default user role)
* Possibility to login or logout
* User can:
    * see all movies
    * see all cinema halls
    * see available movie sessions
    * add tickets to shopping cart
    * complete order
* Admin can:
    * find user by email
    * create | see available -> movies
    * create | see -> cinema halls
    * create | change | delete | see -> movie sessions

## :chains: Structure :chains:
* Controller - accepts client requests and displays information in the browser
* Service - сontains all the business logic of our application
* DAO - Contains all communication with the database

## :man_technologist: Technologies :man_technologist:
* Java 11
* Maven
* MySQL
* Tomcat 9.0.50
* Hibernate
* Spring MVC
* Spring Security

## :bulb: How it works? :bulb:
* Step 1 - Fork this repository
* Step 2 - Open IntelliJ IDEA and write git clone <SSH link> in your console.
* Step 3 - Configure resources --> "db.properties" file
```
db.driver=YOUR_DRIVER
db.url=YOUR_URL
db.user=YOUR_USERNAME
db.password=YOUR_PASSWORD
```
* Step 4 Install [Apache Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)
* Step 5 Configure Apache Tomcat
* Start the application

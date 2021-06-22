# Cinema application (in progress)
A quite simple REST application that represents the work of the cinema.
![pic](Cinema_Uml.png)

A person without role can:
-
- register
- view all available movie sessions
- view all movies
- view all cinema halls

A user can:
-
- add the ticket for movie to the shopping cart
- view all the tickets in the shopping cart
- process the order
- view a history of all the orders


An admin can:
- 
- view a list of all films
- find user by email
- create new film
- create new cinema hall
- create new movie session, and also delete and update it.

## **Technologies used**

- Spring - Core / MVC / Web / Security
- Hibernate
- DataBase - MySQL
- Packaging - Apache Maven
- Tomcat

## **Configuration:**

- Сlone this project into your local folder and open the project in an IDE.
- Setup new connection in "src/main/resources/db.properties" and set your: driver, url, username and password
- Configure Tomcat (Local) with : Deployment - war_exploded, context address - "/"
- Run a project
- Admin and User will be added to your database when program start. You can log in as: Admin: (name: "alice@gmail.com", password:"12345"), or
  User: (name: "bob@gmail.com", password:"1234")

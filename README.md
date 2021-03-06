# JAX-RS REST E-Commerce Web Service
### An-E-Commerce-RESTful-built-using-JAX-RS.

## ð Documentation
ð§[Postman RESTful API Docs](https://documenter.getpostman.com/view/8951496/UyxdK91c)

## ð¦ Features
* HATEOAS
* Custom ExceptionMappers
* Content negotiation (support for both XML and JSON payloads and responses)

## â Technologies used
* JAX-RS (Jersey)
* JSON-B
* JAX-B
* Maven
* Tomcat
* Intellij IDEA Ultimate
* Postman

 ## ð  Run with Maven
    **Maven**
* Change the configuration of Tomcat in `pom.xml`. 
* Deploy the application using the following maven command:
 ```
mvn clean compile tomcat7:redeploy
```
* REST: change the URL in the Postman collection environment variables to match the port you chose for your Tomcat deployment

**ð¬MySQL**
* Create a database schema and provide the username and password in the persistence.xml
* Hibernate will automatically create the tables for you

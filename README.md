# crud
**CRUD Project**
This project explains CRUD (Create, Read, Update, Delete) operations using spring boot and H2 in-memory database. In this app we are using Spring Data JPA for built-in methods to do CRUD operations.
@EnableJpaRepositories annotation is used on main class to Enable H2 DB related configuration, which will read properties from application.properties file.


**Build and Run application**
-> mvn clean install
-> run main method from SpringBootH2CRUDApplication.java as spring boot application.

**Tools**
Eclipse or IntelliJ IDEA (or any preferred IDE) with embedded Maven

Maven (version >= 3.6.0)

Postman (or any RESTful API testing tool)

Swagger can be launched in Browser: http://localhost:9010/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config

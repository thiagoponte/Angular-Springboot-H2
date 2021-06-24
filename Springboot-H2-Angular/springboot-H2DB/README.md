# Spring Boot Examples

 This project depicts the Spring Boot Example.

## Description

This Project shows the list of Users which are stored in the In-Memory H2 Database.
Using the following endpoints, different operations can be achieved:
 - `/helloworld` - This returns the `greeting` string from `application.yml`
 - `/helloworld/name` - This returns the value of config `config.app.name` from `application.properties`
 - `/users` - This returns the list of Users in the Users table which is created in H2
 - `/users/name/{name}` - This returns the details of the Users passed in URL
 - `/users/load` - Add new users using the Users model. 
    eg.
     ```
        {
        "name": "John",
        "teamName": "Development",
        "salary": 100
        } 

## Libraries used
 - Spring Boot
 - Spring Configuration
 - Spring REST Controller
 - Spring JPA
 - H2 
 
## Development Tools
 - Git 2.10.0
 - VS Code
 
## Compilation Command
 - `mvn clean install` - Plain maven clean and install
 
## Run Command
- `mvn sprint-boot:run` - Run the app

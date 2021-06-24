# Simple Spring-boot + Angular app

## Tech stack

* Java 8
* Spring-boot
* H2 in-memory Database
* Angular 6

## Instructions

Assuming Ubuntu Linux for the install commands, adjust accordinly to your OS.

### Backend application

Install Java 8: ``` sudo apt install openjdk-8-jdk ```

Install Maven: ``` sudo apt install maven ```

Run maven to download libraries and compile the backend app: ``` mvn clean install ```

Run the backend app: ``` mvn spring-boot:run ```

### Frontend application

Install nvm: https://github.com/nvm-sh/nvm ``` curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash ```


Install Node 10: ``` nvm install lts/dubnium ```

Use Node 10: ``` nvm use 10 ```

Install Angular 6 or higher: https://www.npmjs.com/package/@angular/cli
``` npm install -g @angular/cli@6.1.1 ```

Download libraries: ``` npm i ```

Build app: ``` ng build ```

Run the frontend app: ``` ng serve ```

You can access the application at: http://localhost:4200/

More information on the README files of each app.

# DSCatalog Backend

This project with a REST API developed using Java and Spring Boot. The main entities are the Product, Category and User. This project use Spring Security with Token JWT to validade user's actions and a user can have many Roles, each one has it's own permissions.

## Requirements
* Java 17
* Maven
* Any Java IDE

## How to set up
1. Clone this project to your machine and import it to your favorite IDE
2. Install the project's dependencies using Maven
3. The three basic users created when the project initialize are: 'alex@gmail.com' and 'maria@gmail.com' and the password are '123456' for both. If you want to the change default users, update the file './src/main/resouces/import.sql'
4. Run the project
5. Set up the frontend project, following the instructions [here](https://github.com/Fronchak-Projects/DS-Catalog-Frontend)
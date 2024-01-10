# Employee CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application for managing employee records. It provides RESTful API endpoints for interacting with employee data.

## Table of Contents

- [Introduction](#employee-crud-application)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Configuration](#configuration)
- [Contributing](#contributing)


## Prerequisites

Make sure you have the following installed:

- Java (JDK 8 or later)
- MySQL Database
- Git
- [Spring Boot](https://spring.io/projects/spring-boot)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/poojatajane18/EmployeeCrud.git

The application will start on http://localhost:7090.


## API Endpoints

- GET /EmployeeCrud: Get a list of all employees.  
- GET /EmployeeCrud/{id}: Get details of a specific employee by ID.   
- POST /EmployeeCrud: Create a new employee.   
- DELETE /EmployeeCrud/{id}: Delete an employee by ID.
## Technologies Used

- Java  
- Spring Boot  
- MySQL      
- Hibernate  
- Maven
## Configuration
Configure your database settings in the application.properties file.

spring.datasource.url=jdbc:mysql://localhost:3306/database_name
spring.datasource.username=root
spring.datasource.password=your_password

#Hibernate properties  
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
server.port=7090


## Contributing

Feel free to contribute to the development of this project. Follow these steps:

    1. Fork the repository. 
    2. Create a new branch (git checkout -b feature/new-feature).
    3. Make changes and commit (git commit -m "Add new feature").
    4. Push to the branch (git push origin feature/new-feature).
    5. Create a pull request. 
## Screenshots




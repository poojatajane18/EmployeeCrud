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


![Screenshot (232)](https://github.com/poojatajane18/EmployeeCrud/assets/92642653/8e335d97-0b89-4731-b306-ffc17e6f8a09)


![Screenshot (226)](https://github.com/poojatajane18/EmployeeCrud/assets/92642653/2a1659e9-1523-47c6-bd3c-c7c8a140e1de)


![Screenshot (228)](https://github.com/poojatajane18/EmployeeCrud/assets/92642653/cb134c5e-0409-4f2f-a2db-dc92eb2e0f4e)


![Screenshot (229)](https://github.com/poojatajane18/EmployeeCrud/assets/92642653/02b53c0e-ae02-4751-ad5e-1f6a7d4f7585)


![Screenshot (230)](https://github.com/poojatajane18/EmployeeCrud/assets/92642653/0772687a-3fd0-4cf4-a907-6d65dca7f169)


![Screenshot (231)](https://github.com/poojatajane18/EmployeeCrud/assets/92642653/b874ff15-343f-4183-8333-2955872824bd)












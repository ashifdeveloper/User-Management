# UserManagement Project 

## Frameworks and Language Used


<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
  <a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.0.5-brightgreen.svg" />
</a>
  

</p>

The UserManagement project is developed using the Spring Framework, with Spring Boot as the primary framework for building the backend. The main language used for development is Java.

## Data Flow

### 1. UserController
The `UserController` class handles incoming HTTP requests related to user operations and directs them to the appropriate service methods.

- `getAllUsers()`: This endpoint responds to a GET request to "/users" and retrieves a list of all users.

- `addUsers()`: This endpoint responds to a POST request to "/users" and adds multiple users based on the provided list of user data in the request body.

- `addUser()`: This endpoint responds to a POST request to "/user" and adds a single user based on the provided user data in the request body.

- `getUser()`: This endpoint responds to a GET request to "/getUser/{userId}" and retrieves a single user based on the provided user ID in the request path.

- `updateUserInfo()`: This endpoint responds to a PUT request to "/updateUserInfo/{userId}" and updates the information of a user based on the provided user ID in the request path and the updated user data in the request body.

- `deleteUser()`: This endpoint responds to a DELETE request to "/deleteUser/{userId}" and deletes a user based on the provided user ID in the request path.

### 2. Model Class
The `User` class represents the user entity and is used to store user information. It includes fields for user ID, name, date of birth, email, phone number, and a date field.

### 3. Service
 It contains the business logic and interacts with the repository to handle user-related operations.

## Data Structure Used in Your Project

The primary data structure used in the UserManagement project is the `User` class, which represents the user entity. Additionally, a list of users is used in the `getIntializedList()` bean configuration to provide initial data.

## Project Summary

The UserManagement project is a backend application built using the Spring Framework with Java as the primary programming language. It provides endpoints to perform user management operations, including retrieving all users, adding users, retrieving a single user, updating user information, and deleting users. The project follows a structured data flow pattern, with controllers handling incoming requests and services containing the business logic. It also includes a bean configuration for initializing a list of users with initial data.

## Author

👤 **Mohammad Ashif**

* GitHub: [Mohammad Ashif]( https://github.com/ashifdeveloper)

    
---

## 🤝 Contributing

Contributions, issues and feature requests are welcome.
    
---
    
## Show your support

Give a ⭐️ if this project helped you!
    
---
    
## 📝 License

Copyright © 2023 [Mohammad Ashif]( https://github.com/ashifdeveloper).<br />
    
---

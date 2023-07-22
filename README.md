
# User Management System - Readme

This repository contains a simple Java application for User Management System. It provides functionality to manage user details and perform CRUD operations.

## Tech Stack

The application is built using the following technologies:

- Java
- Spring Boot
- Maven (for dependency management)

## Project Structure

The project is organized into packages to keep related files together:

1. `com.geekster.User.Management.System.models`: This package contains the `User` class, representing the model for user details. It includes attributes like `userId`, `userName`, `dateOfBirth`, `email`, `phoneNumber`, `date`, and `time`.

2. `com.geekster.User.Management.System.controllers`: This package contains the RESTful API controllers that handle incoming requests related to user management. The `UserController` class contains endpoints for adding, updating, retrieving, and deleting user details.

3. `com.geekster.User.Management.System.services`: This package contains the service layer of the application. The `UserService` class provides methods to perform various operations on user details.

4. `com.geekster.User.Management.System.repository`: This package contains the data access layer. The `UserDao` class is a simple in-memory data repository for managing user details.

## Functionality

The application provides the following functionalities:

1. **Add User**: Endpoint to add user details to the system.

2. **Get User by ID**: Endpoint to retrieve user details by user ID.

3. **Get All Users**: Endpoint to retrieve all user details.

4. **Update User**: Endpoint to update user details by user ID.

5. **Delete User**: Endpoint to delete user details by user ID.

## Controller

The Controller layer is responsible for handling incoming HTTP requests and returning appropriate responses. It interacts with the Service layer to perform various operations on user details. The `UserController` class contains endpoints for user management:

- **Add User**: Endpoint to add user details to the system.

- **Get User by ID**: Endpoint to retrieve user details by user ID.

- **Get All Users**: Endpoint to retrieve all user details.

- **Update User**: Endpoint to update user details by user ID.

- **Delete User**: Endpoint to delete user details by user ID.

## Service

The Service layer contains the business logic of the application. The `UserService` class is responsible for implementing various operations related to user details. It interacts with the Repository layer to access the data. The `UserService` class provides the following methods:

- **Add User**: Method to add user details to the system.

- **Get User Details**: Method to retrieve user details by user ID.

- **Get All User Details**: Method to retrieve all user details.

- **Update User Details**: Method to update user details by user ID.

- **Delete User**: Method to delete user details by user ID.

## Repository

The Repository layer is responsible for data access and communication with the database. In this case, the `UserDao` class acts as a simple in-memory data repository for user details.

## Getting Started

To run the application locally, follow these steps:

1. Ensure you have Java JDK and Maven installed on your system.

2. Clone this repository to your local machine.

3. Open the project in your preferred Java IDE.

4. Build the project using Maven.

5. Run the application.

6. The application should now be running, and you can use tools like Postman to test the RESTful API endpoints.

## Contributing

If you wish to contribute to this project, feel free to create pull requests or open issues for improvements or bug fixes.



- ArrayList

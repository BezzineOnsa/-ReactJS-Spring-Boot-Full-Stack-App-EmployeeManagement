# Employee Management System

This repository contains a simple **Employee Management System** implemented using **Spring Boot** for the backend and **React** for the frontend. The system provides basic CRUD (Create, Read, Update, Delete) operations for managing employee records.

## Backend (Spring Boot)

### Technologies Used
- **Spring Boot**
- **Spring Data JPA**
- **MySQL Database**

### Project Structure

- **com.bezzine.springboot.controller:** Contains the main controller class (`EmployeeController`) responsible for handling HTTP requests related to employee operations.
  
- **com.bezzine.springboot.exception:** Defines a custom exception class (`ResourceNotFoundException`) for handling resource not found scenarios.
  
- **com.bezzine.springboot.model:** Contains the `Employee` entity class, representing the structure of an employee record in the database.
  
- **com.bezzine.springboot.repository:** Defines the `EmployeeRepository` interface, extending `JpaRepository` for database operations.

### Configuration
- `application.properties`: Contains configuration properties for the Spring Boot application, including the database connection details.

### Running the Backend
1. Ensure you have a MySQL database running.
2. Set up the database connection details in the `application.properties` file.
3. Run the Spring Boot application.

## Frontend (React)

### Technologies Used
- **React**
- **Axios**
- **Bootstrap**

### Project Structure

- **src/services:** Contains the `EmployeeService` class responsible for making HTTP requests to the backend.
  
- **src/components:** Contains React components for different pages, such as listing employees, creating and updating employees, and viewing employee details.

### Dependencies
- **Axios:** For making HTTP requests to the backend.

### Running the Frontend
1. Install the required dependencies using `npm install`.
2. Run the React application using `npm start`.

## Usage

1. Access the application at [http://localhost:3000](http://localhost:3000) (assuming the React development server is running).
2. Perform CRUD operations on employee records using the provided UI.

## Backend API Endpoints

- **GET /api/v1/employees:** Retrieve all employees.
  
- **POST /api/v1/employees:** Create a new employee.
  
- **GET /api/v1/employees/{id}:** Retrieve details of a specific employee by ID.
  
- **PUT /api/v1/employees/{id}:** Update details of a specific employee by ID.
  
- **DELETE /api/v1/employees/{id}:** Delete a specific employee by ID.

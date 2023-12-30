# Employee Management System

This repository contains a sophisticated Employee Management System implemented using Spring Boot for the backend and React for the frontend. The system seamlessly provides robust CRUD (Create, Read, Update, Delete) operations for efficiently managing employee records.

## Backend (Spring Boot)

### **Technologies Used**
- **Spring Boot**
- **Spring Data JPA**
- **MySQL Database**

### **Project Structure**

- **com.bezzine.springboot.controller:** Orchestrates the primary controller class (`EmployeeController`) adept at handling HTTP requests concerning employee operations.
  
- **com.bezzine.springboot.exception:** Encompasses a custom exception class (`ResourceNotFoundException`) tailored for gracefully handling resource not found scenarios.
  
- **com.bezzine.springboot.model:** Houses the `Employee` entity class, delineating the blueprint of an employee record in the database.
  
- **com.bezzine.springboot.repository:** Defines the `EmployeeRepository` interface, extending `JpaRepository` for streamlined database operations.

### **Configuration**
- `application.properties`: Hosts configuration properties for the Spring Boot application, including meticulous database connection details.

### **Running the Backend**
1. Ensure a MySQL database is operational.
2. Configure the database connection details in the `application.properties` file.
3. Execute the Spring Boot application.

## Frontend (React)

### **Technologies Used**
- **React**
- **Axios**
- **Bootstrap**

### **Project Structure**

- **src/services:** Harbors the `EmployeeService` class, the architect of HTTP requests to the backend.
  
- **src/components:** Showcases React components for varied pages, encompassing employee listing, creation and modification, and detailed employee view.

### **Dependencies**
- **Axios:** Empowers HTTP requests to the backend.

### **Running the Frontend**
1. Install the requisite dependencies with `npm install`.
2. Activate the React application with `npm start`.

## **Usage**

1. Access the application at [http://localhost:3000](http://localhost:3000) (assuming the React development server is operational).
2. Execute seamless CRUD operations on employee records through the intuitive user interface.

## Backend API Endpoints

- **GET /api/v1/employees:** Retrieve all employees.
  
- **POST /api/v1/employees:** Forge a new employee record.
  
- **GET /api/v1/employees/{id}:** Acquire details of a specific employee by ID.
  
- **PUT /api/v1/employees/{id}:** Overhaul specifics of a designated employee by ID.
  
- **DELETE /api/v1/employees/{id}:** Eradicate a specified employee by ID.

## **Contributing**

Feel empowered to contribute to the evolution of this sophisticated Employee Manag

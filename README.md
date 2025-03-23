# Ecommerce_Day2

## Overview
This is a simple Spring Boot application that provides two REST API endpoints. It demonstrates the use of `@RestController`, `@RequestMapping`, and `@GetMapping` annotations.

## Technologies Used
- Java
- Spring Boot
- Maven

## Project Structure
```
lk.ac.vau.fas.ict.Controller
  |-- AppController.java
  |-- StudentController.java
```

## Setup and Running the Application
### Prerequisites
- Install Java (JDK 8 or later)
- Install Maven
- Install Spring Boot

### Steps to Run
1. Clone the repository or create a new Spring Boot project.
2. Ensure dependencies are installed via Maven.
3. Run the application using:
   ```sh
   mvn spring-boot:run
   ```
4. Access the endpoints in a browser or Postman:
   - `http://localhost:8080/app/msg` → Returns: **Hello**

     
   - `http://localhost:8080/app/name` → Returns: **My name is SpringBoot**


  - `http://localhost:8080/student/myname` → Returns: **My name is Savindu**
    
  




## License
This project is open-source and available for educational purposes.

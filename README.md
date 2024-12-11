# Spring Boot Authentication and Authorization Example
This project demonstrates a simple authentication and authorization system using Spring Boot, JWT, and Spring Security. It includes endpoints for user registration, login, and accessing secured resources based on user roles.

### Features
- User Signup and Login: Users can register and log in to get a JWT token.
- JWT-based Authentication: Secures endpoints using JWT tokens.
- Role-based Authorization: Access control using roles (e.g., USER, ADMIN).
- Spring Security: Handles authentication and authorization.

### Technologies Used
- Spring Boot
- Spring Security
- JWT (JSON Web Tokens)
- MySql Database (or replace with your preferred DB)
- Lombok (for reducing boilerplate code)
- Maven (for dependency management)

## Getting Started
### Prerequisites
- Java 17+
- Maven
- IDE (e.g., IntelliJ IDEA, Eclipse)
- Postman or cURL (for testing APIs)
- Running the Application



#### Clone the repository:

```
git clone <repository-url>
cd <repository-folder>
```

#### Build the project:
``
mvn clean install
``

#### Run the application:
``
mvn spring-boot:run
``

#### The application will be available at: http://localhost:8080

## API Endpoints on postman
[JWT security.postman_collection.json](https://github.com/user-attachments/files/18100502/JWT.security.postman_collection.json)


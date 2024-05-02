# Registration and Login System
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/vinimeneses/registration-login-system/blob/main/LICENSE)

# About the Project

Secure Login System is a full stack web application built using Java, Spring Boot, Thymeleaf, Spring Security, Jpa/Hibernate and Bootstrap .
The application provides a secure login and registration system, using Spring Security for authentication and authorization, and BCrypt for password encryption.
The user details are stored and retrieved from a database using Spring Data JPA. The application also has a role-based access control system. The user interface is designed using Thymeleaf templates.

## Layout
![image](https://github.com/vinimeneses/registration-login-system/assets/142733323/c62475de-4b32-4596-8f8e-a5177a8208c8)
![image](https://github.com/vinimeneses/registration-login-system/assets/142733323/1838cd4e-a188-440f-9aba-fe56cb06724e)
![image](https://github.com/vinimeneses/registration-login-system/assets/142733323/35f3495a-a6f5-4aff-a327-c1046da5f20b)


# Technologies Used
## Back end
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Maven
## Front end
- Thymeleaf
## Database
- MySQL

# How to Run the Project

## Pré-requisitos: 
- Java 17
- Maven 
- MySQL

```bash
# clone o repositório
git clone https://github.com/vinimeneses/registration-login-system.git

# entre no diretório do projeto
cd registration-login-system

# execute o projeto com Maven
mvn spring-boot:run
```

## Database Setup

This project uses MySQL as its database. Follow the steps below to set up the database:

1. Install MySQL if you haven't done so already. You can download it [here](https://dev.mysql.com/downloads/installer/).
2. Open MySQL Workbench (or any other database client of your choice) and create a new database named `secure_login_system`.
3. Update the `application.properties` file in `src/main/resources` with your MySQL credentials.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/secure_login_system
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
```

## Author
Vinícius Meneses
[Linkedin Profile](https://www.linkedin.com/in/vinimeneses/)

# Java Spring Boot CRUD Application

## 📌 Project Overview

This project is a Java-based web application built using Spring Boot. It demonstrates CRUD (Create, Read, Update, Delete) operations for managing person records through a web interface.

## 🛠️ Technologies Used

- **Java:** 8
- **Spring Boot:** 2.1.9.RELEASE
- **Maven:** Build and dependency management
- **Spring MVC:** Web request handling
- **Thymeleaf:** Server-side HTML templates
- **Embedded Apache Tomcat:** Web server

## ✨ Features

- View person records
- Add new person records
- Search person records
- Edit existing records
- Delete person records

## 📋 Prerequisites

Install the following before running the application:

- Java JDK 8 or a compatible supported JDK
- Apache Maven
- Git

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ranjith2695/java.git
cd java
```

### 2. Build the application

Run the following command from the project root, where `pom.xml` is located:

```bash
mvn clean package
```

### 3. Run the application

```bash
java -jar target/demo-sin-bd-0.0.1-SNAPSHOT.jar
```

### 4. Access the application

Open your browser and visit:

```text
http://localhost:8083/
```

The application is configured to use port `8083`.

## ⚙️ Configuration

Application settings are maintained in:

`src/main/resources/application.properties`

Example configuration:

```properties
server.port=8083
spring.thymeleaf.cache=false
```

## 📁 Project Structure

```text
java/
├── pom.xml
├── src/
│   └── main/
│       ├── java/
│       │   └── com/crud/
│       └── resources/
│           ├── application.properties
│           └── templates/
└── target/
```

## 👨‍💻 Author

**Ranjith Kumar B R**

GitHub: [ranjith2695](https://github.com/ranjith2695)

## 📄 License

No license has been specified. Add a license file if you intend to distribute the project under particular terms.

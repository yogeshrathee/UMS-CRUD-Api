# University Management System (UMS)

Welcome to the University Management System (UMS) project! This system provides functionalities to manage student records within a university.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- CRUD operations for managing student records
- RESTful API for programmatic interaction
- Spring Boot application for easy setup and deployment

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- RESTful API

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Java Development Kit (JDK)
- Maven
- Git


 **Access the Application**:
- Open a web browser and go to `http://localhost:8080/ums`.

## API Endpoints

- **GET /ums/{regNo}**: Get student details by registration number.
![](Screenshot (12).png)
- **GET /ums**: Get all student details.
- **POST /ums**: Create a new student record.
- **PUT /ums**: Update an existing student record.
- **DELETE /ums/{regNo}**: Delete a student record by registration number.
- **DELETE /ums**: Delete all student records.

## Contributing

Contributions are welcome! Please feel free to fork the repository and submit pull requests with your improvements.

## License

This project is licensed under the [MIT License](LICENSE).


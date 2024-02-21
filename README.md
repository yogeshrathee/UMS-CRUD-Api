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
![DataBase](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/1cae2e8545b69312d929d0d8218a81bb0fade2e0/images/Screenshot%20(12).png)
![Get By Id](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/1cae2e8545b69312d929d0d8218a81bb0fade2e0/images/Screenshot%20(13).png)
- **GET /ums**: Get all student details.
- ![Get All records](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(19).png)
- **POST /ums**: Create a new student record.
- ![Create Record](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(14).png)
- **PUT /ums**: Update an existing student record.
- ![Update Record](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(15).png)
- ![Update Record in DataBase](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(16).png)
- **DELETE /ums/{regNo}**: Delete a student record by registration number.
- ![delete By Id](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(17).png)
- ![Delete Id show in database](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(18).png)
- **DELETE /ums**: Delete all student records.
- ![Delete All records](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(20).png)
- ![Delete All record show in database](https://github.com/yogeshrathee/UMS-CRUD-Api/blob/fb8388bed91ca44d726e3ead7f5ac65697d63a4e/images/Screenshot%20(22).png)

## Contributing

Contributions are welcome! Please feel free to fork the repository and submit pull requests with your improvements.

## License

This project is licensed under the [MIT License](LICENSE).


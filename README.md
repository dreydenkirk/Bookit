# 📚 Bookit - A Modern Library Management System

![Bookit Logo](https://img.shields.io/badge/Bookit-Library%20Management%20System-blue.svg)
[![Releases](https://img.shields.io/badge/Releases-latest-orange.svg)](https://github.com/dreydenkirk/Bookit/releases)

Welcome to **Bookit**, a modern library management system built with C# and .NET. This project aims to simplify library operations, providing features for lending, managing fines, and more. It follows best practices, such as the Repository Pattern and Unit of Work, ensuring a clean and maintainable codebase.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Lending Management**: Easily manage book loans and returns.
- **Fine Calculation**: Automatically calculate fines for overdue books.
- **Repository Pattern**: Utilize the Repository Pattern for data access.
- **Unit of Work**: Ensure transactional integrity with the Unit of Work pattern.
- **AutoMapper**: Simplify object mapping with AutoMapper.
- **Logging**: Implement logging with Serilog for better monitoring.
- **Caching**: Improve performance with caching strategies.
- **API Documentation**: Automatically generate API documentation using Swagger.

## Technologies Used

This project utilizes a variety of technologies to enhance functionality and maintainability:

- **C#**: The primary programming language for the application.
- **.NET Core**: The framework used for building the application.
- **Entity Framework Core**: An ORM for data access.
- **Dependency Injection**: For managing dependencies efficiently.
- **SQL**: For database management.
- **RESTful API**: To interact with the application.
- **SOLID Principles**: To ensure code quality and maintainability.

## Getting Started

To get started with Bookit, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/dreydenkirk/Bookit.git
   cd Bookit
   ```

2. **Install Dependencies**:
   Ensure you have the necessary dependencies installed. You can do this using the .NET CLI:
   ```bash
   dotnet restore
   ```

3. **Set Up the Database**:
   Configure your database settings in the `appsettings.json` file. Make sure to create the database specified in the configuration.

4. **Run Migrations**:
   Apply the migrations to set up your database schema:
   ```bash
   dotnet ef database update
   ```

5. **Start the Application**:
   Run the application using:
   ```bash
   dotnet run
   ```

6. **Access the API**:
   Open your browser and navigate to `http://localhost:5000/api`. You can also explore the API documentation at `http://localhost:5000/swagger`.

For the latest releases, you can check out [this link](https://github.com/dreydenkirk/Bookit/releases). Download the latest version and execute it as needed.

## Usage

After setting up the application, you can use the following endpoints:

- **GET /api/books**: Retrieve a list of all books.
- **POST /api/books**: Add a new book to the library.
- **PUT /api/books/{id}**: Update the details of a book.
- **DELETE /api/books/{id}**: Remove a book from the library.
- **GET /api/lendings**: View current lending records.
- **POST /api/lendings**: Lend a book to a user.
- **GET /api/fines**: Check fines for overdue books.

Refer to the Swagger documentation for more detailed information on each endpoint.

## Contributing

Contributions are welcome! If you want to help improve Bookit, follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right corner of the page.
2. **Create a Branch**: Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature/my-feature
   ```
3. **Make Your Changes**: Implement your changes in the code.
4. **Commit Your Changes**: Commit your changes with a descriptive message.
   ```bash
   git commit -m "Add new feature"
   ```
5. **Push to Your Fork**: Push your changes to your forked repository.
   ```bash
   git push origin feature/my-feature
   ```
6. **Create a Pull Request**: Open a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Author**: Dreyden Kirk
- **Email**: dreydenkirk@example.com
- **GitHub**: [dreydenkirk](https://github.com/dreydenkirk)

For the latest releases, visit [this link](https://github.com/dreydenkirk/Bookit/releases). Download the latest version and execute it as needed.

Thank you for checking out Bookit! We hope you find it useful for managing your library effectively.
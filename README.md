# AuthSystem

A simple login and registration system built with .NET 8, focusing on secure authentication and user management.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction
This project provides a basic yet secure user authentication system, implementing registration and login functionalities using .NET 8. It ensures secure password handling and user authentication.

## Features
- User registration
- User login with token-based authentication
- Secure password storage
- JWT token generation and management

## Technologies
- **.NET 8**
- **Entity Framework Core**
- **SQL Server**
- **JWT (JSON Web Token)**
- **Swagger** for API documentation

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abdorhl/AuthSystem.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd AuthSystem
   ```

3. **Install dependencies:**
   Ensure .NET 8 SDK is installed, then restore dependencies:
   ```bash
   dotnet restore
   ```

4. **Set up the database:**
   Update the `appsettings.json` with your SQL Server connection string, then run:
   ```bash
   dotnet ef database update
   ```

5. **Run the application:**
   ```bash
   dotnet run
   ```
## License

This project is licensed under the MIT License.

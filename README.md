# Employee Management Application

## Overview

The Employee Management Application is a Java-based desktop application that allows users to manage employee information. The application supports multiple languages (English, Farsi, and Japanese) and stores employee data in a MySQL database.

## Features

- Add new employee records with first name, last name, and email
- Switch between different languages (English, Farsi, Japanese)
- Store employee data in language-specific tables in a MySQL database

## Technologies Used

- Java
- JavaFX
- Maven
- MySQL
- Dotenv

## Setup Instructions

### Prerequisites

- Java Development Kit (JDK) 11 or higher
- Apache Maven
- MySQL database

### Configuration

1. Clone the repository
2. Create a `.env` file in the root directory with the following content:
   ```
   DB_URL=jdbc:mysql://localhost:3306/employees
   DB_NAME=employees
   DB_USERNAME=your_db_username
   DB_PASSWORD=your_db_password
   ```
3. Update the `pom.xml` file if necessary to match your environment

### Running the Application

1. Open a terminal and navigate to the project directory
2. Run the following Maven command to start the application:
   ```bash
   mvn clean javafx:run
   ```

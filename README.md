## Full-Stack Employee Management System
## Overview
This repository hosts a comprehensive full-stack web application crafted with the Java Spring Framework for the backend and React.js for the frontend. The system features JWT-based authentication and authorization and implements complete CRUD operations to manage employee data. This project is ideal for beginners and experienced developers looking to explore and contribute to a fully functional, real-world web application.

Feel free to clone, deploy, and contribute to this open-source gem!

Tech Stack
## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens)
![PostgreSQL](https://img.shields.io/badge/PostgresSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Chakra UI](https://img.shields.io/badge/Chakra%20UI-319795?style=for-the-badge&logo=chakra%20ui&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## Key Features
JWT-based Authentication & Authorization: Secure user management with login, registration, and role-based access.
Full CRUD Functionality: Manage employee data with the ability to create, read, update, and delete records.
Password Management: Users can reset and change passwords securely.
Responsive Frontend UI: Built using React.js and styled with Chakra UI for a clean, modern interface.
Backend Integration: Backend powered by Java Spring, utilizing Spring Security, Spring Data JPA, and Spring JDBC.
Postgres Database Support: Storing user and employee data securely with Postgres as the database solution.
Docker Support: Easily deployable with Docker for streamlined setup and deployment.


# Fullstack Employee Management

This project consists of both backend (Spring Framework) and frontend (React) components. Follow the steps below to set up and run the application.

## Backend (Spring Framework)

### Steps to Set Up and Run the Backend:

1. **Clone the repository:**
   ```bash
   git clone git@github.com:msbeigiai/fullstack-employee-management.git
Navigate to the project directory:

bash
Copy code
cd fullstack-employee-management
Database Setup: Ensure your Postgres database is up and running before starting the application. You can install Postgres either using Docker or by downloading it from the official website, depending on your operating system (Mac, Linux, or Windows).

After setting up Postgres, create the necessary database by running the following SQL query:
sql
Copy code
CREATE DATABASE employee_db;
Run the backend application: Navigate to the backend folder and run the following commands:

bash
Copy code
cd fullstack-employee-backend
mvn clean run
This will start the Spring backend application.

Frontend (React)
Steps to Set Up and Run the Frontend:
Navigate to the frontend directory:

bash
Copy code
cd ../fullstack-employee-frontend
Run the frontend application: Use the following command to start the frontend development server:

bash
Copy code
npm run dev

## Contributions
My Contributions
As a contributor to this project, my primary contributions included:

## Backend Development:

Integrated Spring Security for robust JWT-based authentication and role-based authorization.
Implemented CRUD operations for managing employee data using Spring Data JPA and Postgres.
Set up RESTful APIs to interact with the frontend, ensuring smooth communication between the backend and frontend components.
## Frontend Development:

Built reusable and responsive UI components using React.js and Chakra UI.
Managed routing with ReactRouter to navigate between different views (login, dashboard, add employee).
Implemented state management for handling form inputs and API responses.
Database Setup:

Designed the schema for employee management in Postgres and ensured seamless integration with the backend.
Dockerization:

Configured Docker for both the backend and database, simplifying the setup process for deployment and development.
## Impact of Contributions
The integration of JWT authentication significantly enhanced the security of the application, ensuring that only authorized users can access specific data and features.
By implementing CRUD operations effectively, I enabled users to manage employee data efficiently and securely, improving overall usability.
The use of Docker improved the development experience by making the application easier to deploy and maintain across different environments.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

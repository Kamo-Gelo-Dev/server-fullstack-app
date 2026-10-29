Markdown
# Server Management Fullstack Application

A full-stack web application built with Spring Boot (Backend) and Angular (Frontend). This project allows users to manage and monitor servers, ping them for status, and filter through server lists.

## 📂 Project Structure

This repository is structured as a monorepo containing both the frontend and backend applications:

*   **`/backend/server`**: The Spring Boot REST API.
*   **`/frontend/serverapp-v16`**: The Angular user interface.

## ⚙️ Prerequisites

Before you begin, ensure you have the following installed:
*   [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) (v11 or higher)
*   [Node.js and npm](https://nodejs.org/)
*   [Angular CLI](https://angular.io/cli) (`npm install -g @angular/cli`)
*   MySQL Server (or your configured database)

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### 1. Clone the repository

bash
git clone [https://github.com/Kamo-Gelo-Dev/server-fullstack-app.git](https://github.com/Kamo-Gelo-Dev/server-fullstack-app.git)
cd server-fullstack-app
2. Running the Backend (Spring Boot)
Navigate to the backend directory:

Bash
cd backend/server
Update your database credentials in src/main/resources/application.yml (or .properties).

Run the application using the Maven wrapper:

Bash
# On macOS/Linux
./mvnw spring-boot:run

# On Windows
mvnw.cmd spring-boot:run
The backend server will start on http://localhost:8080.

3. Running the Frontend (Angular)
Open a new terminal window and navigate to the frontend directory from the root of the project:

Bash
cd frontend/serverapp-v16
Install the necessary Node modules:

Bash
npm install
Start the development server:

Bash
ng serve
The frontend application will start on http://localhost:4200.

🛠️ Built With
Spring Boot - Backend framework

Angular - Frontend framework

MySQL - Relational Database

Bootstrap - CSS Framework

👨‍💻 Author
Kamogelo Makgoba - Kamo-Gelo-Dev

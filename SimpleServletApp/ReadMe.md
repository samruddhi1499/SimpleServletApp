# SimpleServletApp

## Overview
`SimpleServletApp` is a J2EE web application designed to demonstrate the setup and deployment of a simple servlet using Eclipse, Apache Tomcat, MySQL, and GitHub. This project includes instructions for setting up the development environment, creating a servlet, using GitHub for version control, and deploying the application using Podman.

## Prerequisites
Before you begin, ensure you have the following installed:

- **Eclipse IDE for Java Developers**: [Download Eclipse](https://www.eclipse.org/downloads/)
- **Apache Tomcat 10**: [Download Tomcat](https://tomcat.apache.org/)
- **MySQL**: [Download MySQL](https://dev.mysql.com/downloads/)
- **Podman**: [Install Podman](https://podman.io/getting-started)
- **GitHub Account**: [Sign up for GitHub](https://github.com/)

## Project Setup

### 1. Setting Up the Development Environment

1. **GitHub**:
   - Install GitHub and create an account.
   - Set up GitHub Desktop or Git Bash.

2. **Eclipse IDE**:
   - Download and install Eclipse IDE for Java Developers.

3. **Apache Tomcat 10**:
   - Install and configure Apache Tomcat 10.
   - Add Tomcat to Eclipse as a runtime environment.

4. **MySQL**:
   - Install MySQL and create a simple database.
   - Optionally, install MySQL Workbench for database management.

5. **Podman**:
   - For Windows: Install WSL and configure Podman.
   - For macOS/Linux: Install Podman natively.

### 2. Creating and Testing a Simple Servlet Application

1. **Project Setup**:
   - Create a new Dynamic Web Project in Eclipse named `SimpleServletApp`.

2. **Create a Servlet**:
   - Implement a servlet to display a simple "Welcome to J2EE Web Components Lab" message. See `WelcomeServlet.java` for implementation details.

3. **Testing**:
   - Run the servlet using the configured Tomcat server in Eclipse.
   - Access the servlet at `http://localhost:8080/SimpleServletApp/welcome`.

### 3. Using GitHub for Version Control

1. **Repository Setup**:
   - Create a new repository on GitHub named `SimpleServletApp`.
   - Set up `.gitignore` and `README.md` files.

2. **Committing and Pushing**:
   - Initialize Git in your local project directory.
   - Add and commit your servlet application.
   - Push it to your GitHub repository.

3. **Branching**:
   - Create a branch named `feature-servlet` and modify the servlet code (e.g., change the welcome message).
   - Push the changes to the new branch.

### 4. Deploying the Servlet Application with Podman

1. **Run Tomcat in a Podman Container**:
   - Use Podman to run Apache Tomcat inside a container.

2. **Copy and Test the Application**:
   - Copy the servlet project to the container.
   - Test the application in the Podman environment by accessing it via the browser.

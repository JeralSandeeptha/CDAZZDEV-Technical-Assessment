# Online Learning Platform Web Application

This repository contains all the project details for a `CDAZZDEV Technical Assignment` The project is designed to run seamlessly, providing a high quality frontend and backend repositories for demonstration purposes.

## Table of Contents

- [Overview](#overview)
- [Run the project](#run-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [Database Architecture](#database-architecture)
- [Source Code Management](#source-code-management)
- [Main Focus](#main-focus)
- [Extra Considerations](#extra-considerations)
- [Source Code](#source-code)
- [Improvements](#improvements)
- [Future Enhancements](#future-enhancements)
- [Acknowledgment](#acknowledgment)

## Overview

This project is a full-stack `Online Learning Platform` task web application. The application allows users to enrol to the courses and for admin, it allows to manage users, coures and enrolments. It adheres to clean code principles and SOLID design patterns to ensure maintainability and scalability.

## Run the project

If you want to run theis project, there are serveral ways to run the project.

- If you want to run application quickly you can use docker-compose.yml file.

Install Docker
```bash
sudo apt update
sudo apt install docker.io docker-compose -y
```

Verify Installation
```bash
docker -v
docker-compose -v
```

Clone this github repository
```bash

```

Run the Application
```bash
docker-compose up -d
```

- If you want to run application as repositories you can view the source code with following links. Every repository includes how to run each applications.
- [Go to Users Frontend Repository]()
- [Go to Admin Frontend Repository]()
- [Go to Backend Repository]()

## Features

Follow user stories documentation for more details. [View User Stories Documentation](https://docs.google.com/document/d/1yNVqoIllo876Jt4T9Y6gLWwth1n5UL7cIZdf6gEhqtk/edit?usp=sharing)

## Technologies Used

- `Frontend`: React (TypeScript, Vite)
- `Backend`: Express.js with TypeScript
- `Database`: MongoDB
- `Testing`: Unit Testing: Vitest, End-to-End Testing: Cypress
- `Containerization`: Docker & Docker Compose
- `API Testing` - Postman
- `API Documentation` - Thorugh Postman Publisher
- `UI Libraries` - Material UI
- `Code Editor` - Visual Studio Code

## System Architecture

This project was developed through Monolithic Architecture approach.

![System Architecture](https://res.cloudinary.com/dv9ax00l4/image/upload/v1740689618/arch1.jpeg_lmgmye.png)

## Database Architecture

Simple ER diagram
![ER Diagram]()

## Main Focus

- Implement User Application
- Implement Admin Application
- Implement Backend Application
- Maintain code quality with testing
- Make available to run the project under containerization platform

## Extra Considerations

- Implement user authentication for task management
- Advance user management with access tokens and refresh tokens

## Source Code Management

`Version Control`: Git with GitHub for source code management.

`Branching Strategy`: 
- main branch: Stable production-ready code.
- dev branch: Active development branch.
- test branch: Used for testing new features before merging to dev.
- hotfix branch: Used for critical bug fixes and emergency patches.

![Branching Startergy](https://res.cloudinary.com/dv9ax00l4/image/upload/v1740689988/bs1_ytpamp.png)

## Source Code

You can view the source code with following links.
- [Go to User Frontend Repository]()
- [Go to Admin Backend Repository]()
- [Go to Backend Repository]()

## Improvements

1. `Enhancing Performance and Scalability`
 - Implement server-side pagination for task retrieval instead of fetch all the records.
 - Use caching mechanisms like Redis to store frequently accessed data.

2. `Code Quality and Best Practices`
 - Enhance error handling with proper status codes and meaningful messages.

3. `Security Enhancements`
 - Improve the security with two factor authentication.

4. `Database and API Improvements`
 - Implement API versioning to maintain backward compatibility.

5. `Improved Testing Strategy`
 - Improve the test coverage of the code base.

6. `Docker and Deployment Enhancements`
 - Optimize Docker image sizes by using multi-stage builds.
 - Implement a CI/CD pipeline for automated testing and deployment.

## Future Enhancements

- Implement user authentication for task management
- Introduce real-time task updates using WebSockets
- Enhance UI/UX with better animations and state management
- Optimize database queries with indexing for better performance
- Implement server-side pagination to handle large datasets
- Deploy the application to a cloud platform with CI/CD integration

## Acknowledgment

Thank you for taking the time to review this project. Your feedback is greatly appreciated. Thanks for the `CDAZZDEV Company` to reviewing this technical assignment. For those who refer this project, if you find this project useful, feel free to star the repository on GitHub and share it with others! 
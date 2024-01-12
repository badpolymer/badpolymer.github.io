---
# layout: posts
title:  "Database API and Tests"
date:   2023-12-16 03:27:07 +0000
categories: work
description: A model for comprehensive testing practices and a database testing project designed to automate unit tests and integration tests for a REST API with JSON and the PostgreSQL database.
excerpt: A model for comprehensive testing practices and a database testing project designed to automate unit tests and integration tests for a REST API with JSON and the PostgreSQL database.
tags: 
  - API
  - TypeORM
  - PostgreSQL
  - Docker
  - JSON
  - TDD
  - TypeScript
highlight_home: true
header:
  overlay_image: https://images.unsplash.com/photo-1502691876148-a84978e59af8
  teaser: https://images.unsplash.com/photo-1502691876148-a84978e59af8
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---


> To view and try out this project, go to [GitHub Repo](https://github.com/CC-SQA-23FALL-DBTest-Group1/final) and follow the `README` file.

# Overview
  
I worked on a database test automation project that served as a model for comprehensive testing practices. It's designed to automate unit tests and integration tests for a REST API with JSON. The project utilized Docker to containerize both the Node.js server and PostgreSQL database server, providing a scalable and reproducible testing environment. TypeORM was incorporated to facilitate database interactions and management.

# Project Details
## Objective

The primary objective of the project was to automate testing processes for a REST API backed by a PostgreSQL database. By containerizing the development environment with Docker and implementing TypeORM for database interactions, the project aimed to ensure the functionality of the API while streamlining the testing workflow.

## Technologies Used

- **Frontend:** Not applicable (REST API)
- **Backend:** Node.js, Express.js, TypeScript, TypeORM
- **Database:** PostgreSQL
- **Test:** Jest, Axio
- **Containerization:** Docker

## Features

1. **Docker Containerization:**
   - Utilized Docker to containerize both the Node.js server and PostgreSQL database server.
   - Enabled a consistent and isolated environment for testing, ensuring reproducibility across different systems.

2. **REST API with JSON:**
   - Developed a REST API that communicated with the PostgreSQL database using JSON for data representation.
   - Facilitated seamless integration with various applications and services.

3. **Automated Unit Tests:**
   - Implemented automated unit tests to validate individual components and functions of the API.
   - Ensured the correctness of specific units of code, enhancing the overall reliability of the application.

4. **Automated Integration Tests:**
   - Designed and automated integration tests to evaluate the interaction and compatibility of different components within the API.
   - Assured the proper functioning of the entire system by validating the integration of its various parts.

5. **TypeORM for Database Management:**
   - Integrated TypeORM as the Object-Relational Mapping (ORM) tool to simplify database interactions.
   - Managed database entities and relationships using a TypeScript-based ORM, enhancing the efficiency of database operations.



## Development Approach

- **Role:** Led the development team and actively contributed to the analysis, design, and implementation.
- **Approaches:**
  - **Test-Driven Development (TDD):**
    - Adopted a Test-Driven Development approach, writing tests before implementing features.
    - Iteratively refined the codebase based on test outcomes, ensuring a more robust and reliable application.

  - **Continuous Integration (CI):**
    - Implemented continuous integration practices to automatically run tests upon code changes.
    - Detected and addressed issues early in the development process, promoting code stability.


## Results and Impact

- **Increased Code Reliability:**
  - Automated unit and integration tests significantly increased the reliability of the API codebase.
  - Detected and addressed potential issues early in the development cycle, reducing the risk of bugs in production.

- **Streamlined Testing Workflow:**
  - Docker containerization provided a consistent testing environment, streamlining the testing workflow.
  - Team members could easily replicate the testing environment, ensuring consistent results across different machines.

## Recognition

The project acquired recognition and was selected as the sample project for instructional purposes within the college by the instructor.

## Future Developments

The success of this project lays the groundwork for future developments, such as enhancing the test cases.

<br> 
<br>  
  
---

*Explore the intersection of database testing, containerization, and REST API development with our comprehensive automation project. As a recognized sample project, it serves as a valuable resource for instructors and students alike.*
# JPA Student Data Project

## Overview
This project is a simple Java application using the Java Persistence API (JPA) to store and retrieve student data. The project stores 50 students' data into a MySQL database, including fields such as roll number, name, and marks. The marks are randomly generated with values up to 100.

## Technologies Used
- Java
- JPA (Java Persistence API)
- MySQL Workbench
- Maven

## Project Structure
- **Student.java**: An entity class annotated with JPA annotations representing the `Student` table in the database, with fields for `rollno`, `name`, and `marks`.
- **persistence.xml**: Configuration file for JPA settings, including database connection details and entity management.
- **pom.xml**: Maven configuration file for managing project dependencies.
- **Main.java**: The main class where student data is inserted and JPQL (Java Persistence Query Language) queries are executed to retrieve the data.

## Prerequisites
- JDK 8 or above
- Maven
- MySQL Workbench
- JPA provider (e.g., Hibernate as JPA implementation)

## Setup Instructions
1. **Clone the repository**:
 

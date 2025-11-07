Contact Management System
Project Overview

This project is a web-based Contact Management System that enables users to manage their contacts efficiently.
It includes features such as user registration, login, and full CRUD (Create, Read, Update, Delete) operations on contacts.
The system is built using the Java technology stack with a React.js frontend, focusing on modular design, secure authentication, and maintainable code quality.

Technology Stack
Category	Technologies / Tools
Backend	Java, Spring Boot
Database	SQL Server
ORM	Spring Data JPA, Hibernate
Testing	JUnit, Mockito
Logging	Slf4j, Logback
Frontend	React.js
Code Quality	SonarQube
Version Control	Git
Key Features
User Authentication & Authorization

User registration using email or phone number

Secure login with registered credentials

Option to change password anytime

Contacts Management

Display all contacts in a paginated list

Search or filter contacts by first name or last name

Create, update, and delete contacts

View detailed profile for each contact

Each contact profile includes:

First Name

Last Name

Title

Email Addresses (e.g., work, personal)

Phone Numbers (e.g., work, home, personal)

Application Logging

Implemented using Slf4J and Logback

Logs important events, errors, and user activities

Database and JPA

Spring Data JPA used for data access

SQL Server schema designed for users, contacts, and related entities

Exception Handling

Global exception handling for user-friendly error responses

Logged exceptions for debugging and tracking

Unit Testing

Implemented using JUnit and Mockito

Covers controllers, services, and data access layers

Code Quality

Integrated SonarQube for continuous code quality analysis

Configured rules for Java and JavaScript

React.js Frontend

Developed using React.js for a responsive and interactive interface

Includes dashboards for managing contacts and viewing user profiles

Git Version Control

Uses Git for source code management

Encourages branching, merging, and proper commit practices

Optional Features

Export and Import contacts to/from files for backup or migration

Application Screens
1. Login and Registration Screen

Components

Login Form

Registration Form

Operations

Register a new user

Authenticate login credentials

Redirect to the contact management dashboard upon success

2. Contact Management Screen

Components

Paginated contact list

Buttons for create, update, and delete

Search/filter input

Update contact form

Create contact form

Confirmation modal

Operations

Display all user contacts

Search/filter contacts

Update existing contacts via modal

Add new contacts

Delete contacts with confirmation modal

3. User Profile Screen

Components

User details section

Button to change password

Button to logout

Change password form

Operations

Display user information

Reset password via modal

Logout and clear session

Setup Instructions

Clone the Repository

git clone <repository-url>


Backend Setup

Open the project in your preferred IDE (e.g., IntelliJ IDEA or Eclipse)

Configure application.properties for your SQL Server credentials

Run the Spring Boot application

Frontend Setup

cd frontend
npm install
npm start


Run Tests

mvn test


Code Quality Check

Configure and run SonarQube to analyze the project

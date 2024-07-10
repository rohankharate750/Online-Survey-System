# Online Survey System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Online Survey System is a web application designed to facilitate the creation, distribution, and analysis of surveys. Users can create surveys with multiple question types, distribute them to respondents, and view collected responses through an intuitive interface.

## Features
- User authentication and authorization
- Create, edit, and delete surveys
- Multiple question types (e.g., multiple choice, text, rating)
- Distribute surveys via unique links
- Real-time response collection
- Survey result analysis and export

## Technology Stack
- *Backend:* Java, Spring Boot
- *Frontend:* HTML, CSS, JavaScript, Thymeleaf
- *Database:* MySQL
- *Build Tool:* Maven

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 11 or higher
- Maven 3.6.0 or higher
- MySQL 5.7 or higher

### Installation
1. *Clone the repository:*
   sh
   git clone https://github.com/your-username/online-survey-system.git
   cd online-survey-system
   

2. *Configure the database:*
   Create a MySQL database named survey_system and update the database configuration in src/main/resources/application.properties:
   properties
   spring.datasource.url=jdbc:mysql://localhost:3306/survey_system
   spring.datasource.username=your-username
   spring.datasource.password=your-password
   

3. *Install dependencies and build the project:*
   sh
   mvn clean install
   

### Running the Application
1. *Start the application:*
   sh
   mvn spring-boot:run
   

2. *Access the application:*
   Open your web browser and navigate to http://localhost:8080.

## Usage
1. *Register and log in:*
   Create a new account or log in with your existing credentials.

2. *Create a new survey:*
   Navigate to the "Create Survey" page, enter survey details, and add questions.

3. *Distribute the survey:*
   Share the unique survey link with respondents.

4. *View responses:*
   Access the "Survey Results" page to view and analyze collected responses.

## Contributing
We welcome contributions from the community! If you would like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
   sh
   git checkout -b feature-or-bugfix-name
   
3. Make your changes and commit them with clear messages.
   sh
   git commit -m "Description of the feature or bugfix"
   
4. Push your changes to your forked repository.
   sh
   git push origin feature-or-bugfix-name
   
5. Create a pull request to the main repository.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

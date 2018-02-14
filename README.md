# Java Spring Freelancer Platform (Alpha)

Open Source platform for freelance portals based on Java Spring technology.

## Technology

- Java Spring Boot
- Maven
- Thymeleaf
- MySQL

## Features

- User module (register, login, forgot password)
- Post a job
- Place a bid
- View bids
- Hire freelancer
- Message rooms (jobs and one-to-one)
- Feedback / rating system

## Requirements 

1. Java 8
2. Maven
3. MySQL server

## How to install and run 

### 1. Prepare MySQL

1. Create MySQL database 
2. Import /freelance.sql

### 2. Set your config

1. Copy /src/main/resources/application.properties-sample to /src/main/resources/application.properties
3. Update values to your needs

### 3. Clone GIT repo

1. open CMD or Linux terminal and CD to (eclipse) projects root folder
2. git clone [THIS REPO]

### 4. Run Java app

1. CD to the cloned folder
2. mvn clean install
3. mvn compile
4. mvn spring-boot:run

### 5. Test

1. Open URL in your browser http://localhost:8000
2. (optional) Login with triva89@yahoo.com / 123456 credentials - it has some entries for test

Note: you can also run project from Eclipse:

open project > right click on FreelancePlatformApplication.java > Run As > Java Application

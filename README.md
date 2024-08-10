# Reminder Bot
this application is a reminder bot which sends notification as a message in popular social media like Telegram
## Features
* User registration and login with JWT authentication
* Password encryption using BCrypt
* Role-based authorization with Spring Security
* Customized access denied handling
* Logout mechanism
* Refresh token
* Send message in Telegram
* Use a schedule for sending message
* Connect to mysql db

## Technologies
* Spring Boot 3.2.1
* Spring Security
* JSON Web Tokens (JWT)
* BCrypt
* Maven
* Mysql
 
## Getting Started
To get started with this project, you will need to have the following installed on your local machine:

* JDK 17+
* Maven 3+


To build and run the project, follow these steps:

* Clone the repository: `git clone https://github.com/MehdiYasinzadeh/reminer-bot.git`
* Navigate to the project directory: cd reminder-bot
* Add database "test-reminder" for dev profile and "main-reminder" profile for main to mysql
* fill the item in env like DB_MAIN_DATABASE,DB_TEST_DATABASE, DB_LOCAL_DATABASE, DB_MAIN_USER,root DB_TEST_USER,root
  DB_MAIN_PASSWORD, DB_TEST_PASSWORD, bot_token_test, bot_token_main,
* Build the project: mvn clean install
* Run the project: mvn spring-boot:run

-> The application will be available at http://127.0.0.1:8081/swagger/index.html.

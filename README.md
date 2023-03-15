# Polling App Project

This is a polling app project built using Spring Boot and MySQL. The purpose of this project is to provide users with the ability to create and participate in polls.

## Features

- User authentication and authorization with Spring Security
- Poll creation and deletion functionality
- Poll voting functionality
- Poll results display
- User profile page with poll history and statistics

## Installation

To run this project locally, you'll need to follow these steps:

1. Clone this repository to your local machine.
2. Create a new MySQL database with the name `polling_app`.
3. Open the `application.properties` file located in `src/main/resources` and configure the database connection settings.
4. Run the project using the command `mvn spring-boot:run`.
5. Access the website by visiting `http://localhost:8080/` in your web browser.

## Usage

To use this project, you can create an account by clicking the "Register" button on the home page. Once you have logged in, you can create a poll by clicking the "Create a Poll" button on the dashboard page. You can also participate in existing polls by clicking on them from the home page or the dashboard page.

## Credits

This project was built by [Your Name Here](https://github.com/yourusername) using the following technologies:

- Spring Boot
- MySQL
- Thymeleaf
- Bootstrap

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# About The Project
[Kalaha Board Game](https://en.wikipedia.org/wiki/Kalah)

The goal of this project is to build a web application that runs the game "Kalaha", with all the game rules implemented and processed on the back-end in Java.

<img src="https://i.ibb.co/gDW4wwF/screenshot.png" data-canonical-src="https://i.ibb.co/gDW4wwF/screenshot.png" width="100%" />
Screenshot of the game

## Built With
* [Java 15](https://www.oracle.com/java/technologies/javase-downloads.html)
* [Junit](https://junit.org/junit5/)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
* [H2 Database](https://www.h2database.com/html/main.html)
* [Rest](https://restfulapi.net/)
* [Vanilla Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [HTML 5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Prerequisites

* Java 15
* Maven (Optional)

## Installation

1. Clone the git project to your local repository with:
```sh
 git clone https://gitlab.com/bolcom/guilherme-silveira
```

## Usage

1. In the root folder of the project, run the command:
   ```sh
   mvn spring-boot:run
   ```
2. Alternatively, you can run the project by executing the class found in:
   ```sh
   root/src/main/java/nl/guilhermesilveira/kalaha/Application.java
   ```
3. Open following link on your browser:
   ```sh
   http://localhost:8080
   ```
4. Click on `New Game`

## Architecture

This project follows the MVC architecture. The package structure is organised as follows:

* The `controller` package contains classes that handle HTTP requests.
* The `model` package contains the entity classes.
* The `service` package identifies the application layer that encapsulates the business logic, controls transactions, etc.
* The `repository` package contains the repository interfaces that provide CRUD functionality to the entity classes.
* The `game` package contains the game logic implementation.
* The `form` and `dto` packages contain the classes used to map request parameters.
* The `config` package contains the HTTP Security configuration.
* The `security` package contains the classes responsible for user authentication.

## Contact

Guilherme Silveira - guisilveirabatista@gmail.com

Project Link: [https://gitlab.com/bolcom/guilherme-silveira](https://github.com/your_username/repo_name)

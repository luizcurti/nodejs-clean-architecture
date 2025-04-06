# Node.js Clean Architecture
This repository showcases an implementation of the Clean Architecture pattern using Node.js. The main goal is to provide a modular, scalable, and maintainable backend architecture that separates concerns clearly, enabling easy testing and future growth.

## Technologies Used
- Node.js: Platform for building scalable and high-performance applications.
- Express: Minimalist framework for building RESTful APIs.
- Jest: Testing framework for ensuring the reliability and quality of the code.
- TypeScript: A superset of JavaScript that adds static typing, making the code easier to maintain.

## Architecture
- This project follows the Clean Architecture pattern, which separates the business logic from infrastructure (like frameworks and databases), making the application more modular and flexible to future changes.
- The application is organized as follows:
- Entities: Define the core business rules of the application.
- Use Cases: Implement the business logic and domain rules.
- Interface Adapters: Adapt data to a format that the application can use, including controllers and gateways.
- Frameworks and Drivers: Contain external dependencies like databases, frameworks (Express), and other libraries.

## Running the Application
Clone this repository:
- git clone https://github.com/luizcurti/nodejs-clean-architecture.git

## Navigate to the project directory:
- cd nodejs-clean-architecture

## Install the dependencies:
- npm install

## Run the application:
- npm run start

## To run the tests:
- npm run test

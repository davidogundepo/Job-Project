# JWT-based Authentication System

The JWT-based Authentication System is a web application that provides a secure user authentication and authorization mechanism. It is built using React and Symfony, with the use of LexikJWTAuthenticationBundle. The system allows users to register, log in, and retrieve their user information, ensuring high code quality and security for production readiness and post-launch support.

## Key Features

1. **User Registration**: Users can create an account by providing their name, email address, and password. The system validates the input and securely stores user data.

2. **User Login**: Registered users can log in to the system using their email and password. The system authenticates the user, generates a JWT token using LexikJWTAuthenticationBundle, and provides it to the client for subsequent authenticated requests.

3. **User Information Retrieval**: Authenticated users can retrieve their own user information, including name, email, and address.

4. **User Update**: Users can update their name and address information securely through appropriate routes and forms.

## Additional Requirements

- **Secure by Design Code**: The codebase adheres to secure coding practices and considers common security vulnerabilities, ensuring the system is robust against potential threats.

- **Code Quality**: Emphasizes clean, readable, and well-structured code following best practices and industry standards.

- **Local Development with Docker**: The backend can be run locally using Docker and docker-compose, making it easy to set up the development environment.

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/davidogundepo/Job-Project.git

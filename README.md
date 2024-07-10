# Internshala API

The Internshala API is a backend service designed to manage job and internship postings, as well as student applications. 
Built with Node.js and Express.js, this API supports secure user authentication, resume management for students, and job posting functionalities for employees.

## Features

- **Authentication**: Secure login and registration for students and employees using bcryptjs and jsonwebtoken.
- **Resume Management**: Students can create, update, and delete their resumes.
- **Job and Internship Postings**: Employees can post, update, and delete job and internship listings.
- **Application System**: Students can view, apply for, and track their applications to jobs and internships.
- **Role-Based Access Control**: Different access levels for students and employees.
- **Error Handling**: Robust error handling and validation for all endpoints.
- **Security**: Secure endpoints with JWT authentication and input validation.

## Technologies Used

- **Node.js**: JavaScript runtime for server-side development.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing user and job data.
- **Nodemailer**: Module for sending emails.
- **bcryptjs**: Library for hashing passwords.
- **jsonwebtoken**: Library for generating and verifying JSON Web Tokens.
- **Dotenv**: Module for loading environment variables from a .env file.

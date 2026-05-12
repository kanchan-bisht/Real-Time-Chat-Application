<div align="center">
  <h1>🤖 MERN-CHATBOT WITH OPENAI API</h1>
</div>

<div align="center">

[![Features](https://img.shields.io/badge/Features-blue?style=for-the-badge)](#features)
[![Installation](https://img.shields.io/badge/Installation-green?style=for-the-badge)](#installation)
[![Usage](https://img.shields.io/badge/Usage-yellow?style=for-the-badge)](#usage)
[![Environment Variables](https://img.shields.io/badge/Environment%20Variables-red?style=for-the-badge)](#environment-variables)
[![Technologies Used](https://img.shields.io/badge/Technologies%20Used-gray?style=for-the-badge)](#technologies-used)
[![Project Structure](https://img.shields.io/badge/Project%20Structure-purple?style=for-the-badge)](#project-structure)
[![Security](https://img.shields.io/badge/Security-pink?style=for-the-badge)](#security)

</div>


This project is a ChatBot application built using the MERN stack (MongoDB, Express.js, React, Node.js) and integrated with the OpenAI API for natural language processing.

## Features

- **Natural Language Processing:** Utilizes the OpenAI API to understand and respond to user input.
- **User Authentication:** Secure user login and registration using JWT tokens and encrypted passwords.
- **Message History:** Stores user messages in a database, allowing for message retrieval and deletion.
- **Middleware Chains:** Protects routes and handles errors effectively.
- **Responsive UI:** A clean and intuitive user interface built with React.


## Technologies Used

- **MongoDB:** Database for storing user messages and authentication data.
- **Express.js:** Backend framework to handle API requests and middleware.
- **React:** Frontend library for building the user interface.
- **Node.js:** JavaScript runtime environment for running the server-side code.
- **OpenAI API:** Provides natural language processing capabilities.

## Project Structure

```plaintext
MERN-ChatBot/
│
├── frontend/            # React frontend code
│   ├── public/          # Static files
│   └── src/             # React components, hooks, and pages
│
├── backend/             # Node.js backend code
│   ├── config/          # Configuration files (e.g., database, JWT)
│   ├── controllers/     # Route controllers
│   ├── models/          # Mongoose models
│   ├── routes/          # Express routes
│   ├── middleware/      # Middleware functions
│   └── utils/           # Utility functions
│
└── README.md            # This file
```
## Security

- **JWT Tokens:** Secure authentication with JSON Web Tokens.
- **Password Encryption:** User passwords are securely hashed before storing them in the database.
- **HTTP-Only Cookies:** Tokens are stored in HTTP-only cookies to prevent XSS attacks.

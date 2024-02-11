# Task Management TypeScript Project

A simple task management application built with TypeScript, Express.js, and MongoDB.

## Features

- Create, read, update, and delete tasks.
- Validate task inputs.
- RESTful API endpoints for task management.

## Installation

1. Clone the repository:
git clone <repository-url>
cd First_TypeScript_Project



2. Install dependencies:

npm install


3. Set up environment variables by creating a `.env` file in the root directory:

PORT=<port-number>
MONGODB_URI=<mongodb-connection-uri>

vbnet

## Usage

- To start the development server with auto-reloading using `nodemon`:

npm run serve

- To build the TypeScript files:

npm run build

- To run tests:

npm test


## API Endpoints

- **GET /tasks:** Get all tasks.
- **GET /tasks/:id:** Get a single task by ID.
- **POST /tasks:** Create a new task.
- **PUT /tasks/:id:** Update an existing task.
- **DELETE /tasks/:id:** Delete a task by ID.

## Dependencies

- **Express:** Fast, unopinionated, minimalist web framework for Node.js.
- **Express Validator:** An express.js middleware for validator.js.
- **HTTP Status Codes:** A library of HTTP status codes and their associated messages.
- **Morgan:** HTTP request logger middleware for Node.js.
- **Nodemon:** Monitor for any changes in your source and automatically restart your server.
- **TypeScript:** Typed superset of JavaScript that compiles to plain JavaScript.
- **@types/express:** TypeScript definitions for Express.
- **@types/morgan:** TypeScript definitions for Morgan.
- **@types/node:** TypeScript definitions for Node.js.
- **@types/nodemon:** TypeScript definitions for Nodemon.

## License

This project is licensed under the [ISC License](LICENSE).

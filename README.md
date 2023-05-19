# MERN techNotes

## Description

techNotes is a MERN (MongoDB, Express, React, Node.js) project for managing and organizing technical notes. This README.md provides an overview of the project structure, dependencies, and scripts.

## Installation

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Alex-003/mern-techNotes.git`
2. Navigate to the project directory: `cd mern-techNotes`
3. Install the dependencies: `npm install`

## Usage

Before running the project, make sure to set up the environment variables. Create a `.env` file in the root directory and add the necessary variables. Example:

```
DATABASE_URL=mongodb://localhost:27017/techNotesDB
JWT_SECRET=your-secret-key
```

To start the server, run the following command:

```shell
npm start
```

This will start the Node.js server using the `server.js` file.

For development purposes, you can use the nodemon package to automatically restart the server whenever changes are made. Run the following command:

```shell
npm run dev
```

## Dependencies

The project relies on the following dependencies:

- cookie-parser: A middleware for parsing HTTP cookies. Version: ^1.4.6.

- cors: A package for enabling Cross-Origin Resource Sharing (CORS) in Express. Version: ^2.8.5.

- date-fns: A library for manipulating and formatting dates in JavaScript. Version: ^2.30.0.

- dotenv: A zero-dependency module for loading environment variables from a .env file into process.env.
  version: ^16.0.3.

express: A fast and minimalist web application framework for Node.js. Version: ^4.18.2.

- mongodb: The official MongoDB driver for Node.js. Version: ^5.5.0.

- mongoose: An elegant MongoDB object modeling tool for Node.js. Version: ^7.1.2.

- mongoose-sequence: A plugin for Mongoose that adds auto-incrementing fields to schemas. Version: ^5.3.1.

- uuid: A package for generating RFC-compliant UUIDs (Universally Unique Identifiers). Version: ^9.0.0.

To install these dependencies, run npm install in the project directory.

These can be installed by running `npm install`.

## License

This project is licensed under the ISC License.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.

## Author

Alex Segura

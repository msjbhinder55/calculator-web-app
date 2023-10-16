# calculator-web-app

The MERN Calculator is a web-based application that allows users to perform basic arithmetic calculations and maintains a history of previous calculations. It is built using the MERN (MongoDB, Express, React, Node.js) stack.

![MERN Calculator Screenshot](./screenshot.png)

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Technical Details](#technical-details)
- [Contributing](#contributing)
- [License](#license)

## Features

- Perform basic arithmetic calculations (addition, subtraction, multiplication, division).
- Maintain a history log of previous calculations.
- Clear the current calculation or the entire history log.
- Responsive design for different screen sizes and devices.
- User-friendly interface.

## Demo

See the MERN Calculator in action by visiting the [Live Demo](https://your-live-demo-url.com).

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- MongoDB set up and running.

### Installation

1. Clone this repository:

   git clone https://github.com/yourusername/mern-calculator.git
   cd mern-calculator

2. Install server dependencies:

   cd server
   npm install

3. Install client dependencies:

   cd client
   npm install

### Configuration

1. Create a `.env` file in the `server` directory and configure the following environment variables:

   PORT=5000
   MONGODB_URI=your-mongodb-connection-string
   
### Running the Application

1. Start the server:

   cd server
   npm start

2. Start the client:

   cd client
   npm start

## Project Structure

The project is structured as follows:

- `client`: React front-end application.
- `server`: Node.js and Express back-end server.
- `client/public`: Static assets and index.html.
- `client/src`: React components and application logic.
- `server/routes`: Express route definitions.
- `server/models`: Mongoose models for the MongoDB database.
- `server/controllers`: Logic for handling API requests.

## Technical Details

- Front-End: React, Axios
- Back-End: Node.js, Express
- Database: MongoDB with Mongoose
- Version Control: Git and GitHub

## Contributing

Contributions to this project are welcome! Here's how you can get involved:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and test thoroughly.
4. Submit a pull request to the main repository.

Please refer to the [Contribution Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE).

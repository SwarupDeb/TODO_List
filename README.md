# TODO App

This is a simple TODO app built using Node.js, Express, and MongoDB. The app allows users to create tasks, assign categories, and set due dates for each task. Users can also delete tasks as needed.

## Getting Started

### Prerequisites

To run the TODO app, you need to have the following software installed on your system:

- Node.js (v14 or higher)
- MongoDB (v4 or higher)

### Installing Dependencies

1. Clone this repository to your local machine.
2. In the project directory, run the following command to install the required dependencies:

npm install


### Setting Up the Database

1. Make sure MongoDB is installed and running on your system.
2. Update the MongoDB connection string in `config/mongoose.js` to point to your MongoDB database. The default connection string is:

mongodb://127.0.0.1:27017

### Running the App

1. To start the server, run the following command:

npm start

2. The server will be running on port 7000. Open your web browser and go to `http://localhost:7000` to access the TODO app.

## Features

- Create tasks with descriptions, categories, and due dates.
- View the list of tasks in a tabular format.
- Delete tasks individually or multiple tasks at once.
- A visually appealing moving background for an engaging user experience.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS (Embedded JavaScript) for templating
- Bootstrap for styling

## Directory Structure

TODO-App
|-- config
| |-- mongoose.js
|
|-- models
| |-- task.js
|
|-- public
| |-- assets
| |-- style.css
|
|-- views
| |-- home.ejs
|
|-- index.js
|-- package.json
|-- package-lock.json
|-- README.md


## Acknowledgments

This TODO app is created as a learning project to practice building a full-stack web application using Node.js, Express, and MongoDB.

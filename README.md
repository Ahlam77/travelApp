# Travel App
### This is a web application built using React, Node.js, Express, and JWT API that helps users plan their travels by finding information about popular tourist destinations, flights, accommodations, and activities.

# The project is divided into three folders:

### api: Contains the backend server code that provides a RESTful API for the frontend to interact with.
### admin: Contains the admin dashboard code that allows admin users to manage destinations, flights, accommodations, and activities.
### client: Contains the frontend client code that users interact with to plan their travels.

# Features
### User authentication and authorization using JSON Web Tokens (JWT)
### User profile management
### Search for popular tourist destinations
### Get details about each destination such as climate, local attractions, and best times to visit
### Search for flights to and from a destination
### Search for accommodations such as hotels, apartments, and hostels
### Search for activities to do in a destination
### Admin dashboard for managing destinations, flights, accommodations, and activities

# Installation
### To install and run this project on your local machine, follow these steps:

# Clone the repository: git clone https://github.com/ahlam77/travel-app.git
### Install dependencies for the backend: cd travel-app/api && npm install
### Install dependencies for the admin dashboard: cd ../admin && npm install
### Install dependencies for the frontend client: cd ../client && npm install
### Start the backend server: npm start in the api directory
### Start the admin dashboard: npm start in the admin directory
### Start the frontend client: npm start in the client directory
### The application should now be running on http://localhost:3000.

# Configuration
### The backend server requires a configuration file to be present in the root directory of the project named .env. The following environment variables should be set:

### PORT - The port number that the server will listen on
### DB_URL - The URL of the MongoDB database
### JWT_SECRET - A secret key for signing and verifying JWT tokens
### Here is an example .env file:

### PORT=5000
### DB_URL=mongodb://localhost:27017/travel-app
### JWT_SECRET=my-secret-key
### API
### The backend server provides a REST API that can be used by the frontend to retrieve and store data. The API routes are documented in the api/routes/api.js file.

# Admin Dashboard
### The admin dashboard is a React application that allows admin users to manage destinations, flights, accommodations, and activities. It requires authentication to ### access. The dashboard communicates with the backend server through the API.

# Client
### The frontend client is a React application that users interact with to plan their travels. It communicates with the backend server through the API.

# License
### This project is licensed under the MIT License.

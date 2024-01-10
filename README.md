# Registration
User Registration Form using HTML, CSS, Node.js, and MongoDB
Overview
This project demonstrates a simple user registration form implemented with HTML for the front end, Node.js for the server-side logic, and MongoDB for storing user data. The registration form allows users to sign up with a unique username and password.

Prerequisites
Before running the application, make sure you have the following installed:

Node.js: Download and install Node.js

MongoDB: Download and install MongoDB

Getting Started
Clone the repository:

bash
Copy code
git clone https://github.com/jaihind01/registration.git
Navigate to the project directory:

bash
Copy code
cd registration-form
Install dependencies:

bash
Copy code
npm install
Set up the MongoDB database:

Ensure that MongoDB is running on your machine.
Create a new database named registrationdb.
Configure environment variables:

Create a .env file in the project root and add the following:

env
Copy code
PORT=3000
MONGODB_URI=mongodb://localhost:27017/registrationdb
Adjust the PORT and MONGODB_URI values as needed.

Start the application:

bash
Copy code
npm start
The server will run on http://localhost:3000.

Usage
Visit http://localhost:3000 in your browser to access the registration form. Enter a unique username and password to register.

Folder Structure
public/: Contains static assets such as stylesheets.
views/: HTML files for rendering pages.
routes/: Express.js route files.
controllers/: Logic for handling requests.
models/: MongoDB data models.
Contributing
Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and suggestions are highly appreciated!

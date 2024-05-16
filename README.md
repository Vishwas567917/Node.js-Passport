# Node.js Passport Authentication App

This is a Node.js web application that implements user authentication using Passport.js and MongoDB. It allows users to register, login, and access a protected dashboard page upon successful authentication.

## Features

- User registration with validation
- User login with authentication
- Flash messages for error and success notifications
- Protected dashboard accessible only to authenticated users

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Passport.js
- bcrypt.js
- EJS (Embedded JavaScript) for templating
- Bootstrap for styling
- Font Awesome for icons

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nodejs-passport-authentication.git
2. Install dependencies:
cd nodejs-passport-authentication
npm install
3.Configure MongoDB URI:

Replace YOUR_USERNAME_HERE, YOUR_PASSWORD_HERE, and CLUSTER_NAME_HERE in config/keys.js with your MongoDB Atlas username, password, and cluster name respectively.

4. Run the application:
npm start
5. Visit http://localhost:5000 in your web browser.

Usage
1 Register a new account by visiting /users/register.
2 Login with your registered credentials at /users/login.
3 Access the protected dashboard at /dashboard.
4 Logout by clicking the "Logout" button on the dashboard.


Folder Structure
1 config: Contains configuration files for Passport authentication and MongoDB connection.
2 models: Defines the User model schema for MongoDB.
3 public: Contains static assets such as CSS files and client-side JavaScript.
4 routes: Defines the application routes for handling HTTP requests.
5 views: Contains EJS templates for rendering HTML pages.
6 app.js: Main entry point of the application.


Credits
This project was built based on tutorials and guides available online for Node.js authentication with Passport.js.

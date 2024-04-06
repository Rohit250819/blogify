
# Blogging Application

This is a simple blogging application built with Node.js, Express, MongoDB, EJS, JSON Web Token authentication, and Multer for handling file uploads.

# Features

User Authentication: Users can sign up, sign in, and sign out securely using JSON Web Tokens.

Create Blogs: Authenticated users can create new blog posts with titles, content, and cover images.

View Blogs: Users can view all existing blog posts with their titles, content, and cover images.

Comment on Blogs: Users can leave comments on blog posts to engage with the content.

# Dependencies
Express: Web framework for Node.js.

EJS: Embedded JavaScript templating for generating HTML markup.

MongoDB: NoSQL database for storing user data, blog posts, and comments.

Mongoose: MongoDB object modeling tool for Node.js.

JSON Web Token: Secure authentication mechanism for web applications.

Multer: Middleware for handling file uploads in Express.

# Getting Started

Clone the repository: git clone <repository-url>

Install dependencies: npm install

Set up environment variables: Create a .env file in the root directory and add the following variables:

makefile

Copy code

PORT=3000

MONGODB_URI=<your-mongodb-uri>

JWT_SECRET=<your-jwt-secret>

Start the server:

For development: npm run dev

For production: npm start

Access the application in your web browser at http://localhost:3000

# Folder Structure

app.js: Entry point of the application.

routes/: Contains route definitions for different features.

models/: Defines Mongoose schemas for user data, blog posts, and comments.

views/: Contains EJS templates for rendering HTML pages.

public/: Stores static assets such as CSS stylesheets and client-side JavaScript files.

middleware/: Contains custom middleware functions for authentication and file upload handling.

uploads/: Directory where uploaded blog cover images are stored.

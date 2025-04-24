Overview
Cosmetics Store is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). This project is designed to provide an online platform for users to browse and purchase cosmetics, with functionality for managing products, user authentication, and a shopping cart. It demonstrates the integration of front-end and back-end technologies to create a responsive and dynamic e-commerce website.

Features
User Authentication: Users can register, log in, and manage their account details.

Product Management: Admin users can add, update, or delete products from the store.

Shopping Cart: Users can add items to their shopping cart, view the cart, and proceed to checkout.

Order Processing: Users can place orders, which are saved in the database for further processing.

Search and Filter: Users can search and filter products by category, price, and other attributes.

Technologies Used
MongoDB: NoSQL database for storing user data, product information, and orders.

Express.js: Web framework for building the back-end API.

React.js: Front-end library for building the user interface.

Node.js: JavaScript runtime for server-side development.

JWT (JSON Web Tokens): For secure user authentication.

Mongoose: ODM (Object Data Modeling) library for MongoDB and Node.js.

Redux: State management for the front-end application.

Bcrypt: For password encryption.

Axios: For making HTTP requests to the back-end.

Installation
Prerequisites
Node.js

MongoDB

Clone the repository

git clone https://github.com/otarovvak/Cosmetics-Store-MERN.git
Install dependencies
Navigate to the back-end directory and install the dependencies:


cd server
npm install
Navigate to the front-end directory and install the dependencies:


cd client
npm install
Set up environment variables
In the root of the project, create a .env file and add the following environment variables:

MONGO_URI=<your_mongo_db_connection_string>
JWT_SECRET=<your_jwt_secret_key>

Run the project
Start the back-end server:


cd server
npm start
Start the front-end client:


cd client
npm start
The application will now be running at http://localhost:3000.

Usage
Registration/Login: Navigate to the login or registration page to create or access your account.

Browse Products: View available cosmetics and filter them by category, price, or other attributes.

Add to Cart: Add products to your cart and proceed to checkout.

Place Orders: Once you're ready, place your order for the selected products.

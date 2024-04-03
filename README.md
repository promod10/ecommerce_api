# Ecommerce API with Node.js and Express.js
## Introduction
This project is an ecommerce API built with Node.js and Express.js. It includes user authentication with password hashing using crypto.js and JWT tokens for secure authorization. Additionally, it implements the Stripe payment gateway to enable secure and seamless payments.

## Features
The following are the features of the ecommerce API:
- User authentication with password hashing using crypto.js.
- JWT tokens for secure authorization.
- Integration with Stripe payment gateway for secure payments.
- CRUD operations for products, orders, and users.

## Installation
To use the ecommerce API, follow these steps:
- Clone the repository: `git clone https://github.com/promod10/ecommerce_api.git`
- Install dependencies: `npm install`
- Create a `.env` file and add the following variables:
     - `PORT:` the port number for the server.
     - `MONGO_URI:` the URI for the MongoDB database.
     - `JWT_SECRET:` the secret key for JWT token signing.
     - `STRIPE_SECRET_KEY:` the secret key for the Stripe payment gateway.
- Start the server: `npm start`

## Technologies
- Node.js
- Express.js
- MongoDB
- JWT
- crypto.js
- Stripe


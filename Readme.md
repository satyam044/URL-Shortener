# URL Shortener Backend
A simple and efficient backend service for shortening long URLs.
Built using Node.js, Express, and MongoDB.

## ✨ Features
Shorten long URLs to short, unique links.

Save and retrieve URL mappings from a database.

User authentication using JWT tokens.

Cookie parsing for session management.

Server-side rendered pages using EJS.

Automatic server reloads during development with Nodemon.

## 🚀 Tech Stack
Node.js

Express.js

MongoDB with Mongoose

EJS (for templating)

JWT (for authentication)

NanoID and ShortID (for generating unique short URLs)

UUID (for additional ID management)

## 🛠 Main Functionalities
POST /shorten

Create a shortened URL from a long URL.

GET /:shortId

Redirect to the original long URL.

Authentication Endpoints

Register/Login users and issue JWTs.

Protected Routes

Certain actions require a valid token.
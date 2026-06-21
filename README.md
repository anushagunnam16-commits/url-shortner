# URL Shortener

A backend application that allows users to generate shortened URLs, redirect users to original URLs, and track click analytics.

## Features

- Generate short URLs
- Redirect users using short URLs
- Track click analytics
- Redis caching for faster lookups
- MySQL database persistence
- RESTful API architecture
- Deployed on Render

## Tech Stack

### Backend
- Node.js
- Express.js
- MySQL
- Redis

### Tools
- Git
- GitHub
- Postman
- Render
- VS Code

## API Endpoints

### Create Short URL

POST /shorten

### Redirect URL

GET /:code

### Analytics

GET /analytics/:code

## Project Structure

url-shortener/
│
├── routes/
├── controllers/
├── db.js
├── redisClient.js
├── app.js
├── package.json
└── README.md

## Installation

### Clone Repository

git clone <repo-url>

### Install Dependencies

npm install

### Configure Environment Variables

Create a .env file:

DB_HOST=
DB_USER=
DB_PASSWORD=
DB_NAME=
REDIS_URL=

### Run Application

node app.js

## Future Enhancements

- User authentication
- Custom aliases
- QR code generation
- Detailed analytics dashboard

## Author

Anusha Gunnam

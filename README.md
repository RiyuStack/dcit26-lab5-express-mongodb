# DCIT 26 - Laboratory 5: Express and MongoDB

## Description

A Student Records REST API built using Node.js, Express,
MongoDB, and Mongoose.

## Requirements

- Node.js
- MongoDB Community Server

## Installation

1. Clone the repository.
2. Install the required packages:

   npm install

3. Create a local .env file in the project root.
4. Configure the MongoDB connection and port.

## MongoDB Configuration

MONGODB_URI=mongodb://127.0.0.1:27017/lab5_students

PORT=5000

## Running the Server

Start the development server:

npm run dev

Start the server normally:

npm start

## API Routes

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/health | Check API status |
| GET | /api/students | Get all students |
| GET | /api/students/:id | Get one student |
| POST | /api/students | Create a student |
| PUT | /api/students/:id | Update a student |
| DELETE | /api/students/:id | Delete a student |
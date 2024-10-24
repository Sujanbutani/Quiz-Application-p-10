#  Quiz Application API

This is a simple backend API for managing quizzes and storing user responses using Node.js, Express, and MongoDB.

## Features

- Create new quizzes with questions
- Fetch all quizzes
- Fetch a specific quiz by ID
- Submit user answers and calculate scores

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- dotenv
- nodemon

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sujanbutani/Quiz-Application-p-10.git

2. Install dependencies:

    ```bash
    npm install

3. .env file

     ```
    MONGO_URI=your_mongo_db_connection_string
    PORT=5000
    ```

4. Start the development server:

   ```bash
   npm start
   The server should now be running at http://localhost:5000
   ```

## API Endpoints


### Quiz App
1. Quiz Api (Post - Create Quiz) :- localhost:5000/api/quizzes
3. Quiz Api (Get - All Quizzes) :-  localhost:5000/api/quizzes
4. Quiz Api (Get - One Quiz) :-localhost:5000/api/quizzes/<Quiz_Id>
5. Quiz Api (Post - Submit Quiz) :- localhost:5000/api/quizzes/submit

## Environment Variables
- PORT: The port for the server to listen on.
- MONGO_URI: Your MongoDB connection string.
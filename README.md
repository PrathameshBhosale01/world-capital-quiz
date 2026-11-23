# Country Capitals Quiz

A web-based quiz application built using Node.js, Express.js, EJS and PostgreSQL. The application randomly selects countries from a PostgreSQL database and challenges users to identify their respective capitals.

## Tech Stack
- Node.js
- Express.js
- PostgreSQL
- EJS
- HTML, CSS, JavaScript

## Features
- Random country selection
- Capital identification quiz
- Answer validation
- Score tracking
- PostgreSQL database integration

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/country-capitals-quiz.git
   ```

2. Navigate to the project directory:
   ```bash
   cd country-capitals-quiz
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a PostgreSQL database named `WORLD`.

5. Create the `capitals` table using `database/schema.sql`.

6. Import the dataset from `capitals.csv`.

7. Create a `.env` file using `.env.example` and configure your PostgreSQL credentials.

8. Start the application:
   ```bash
   node index.js
   ```

9. Open your browser:
   ```text
   http://localhost:3000
   ```

## Environment Variables

Configure the following variables in your local `.env` file:

- DB_USER
- DB_HOST
- DB_NAME
- DB_PASSWORD
- DB_PORT

**Note:** Never commit your `.env` file or expose database credentials publicly.

# To-Do List Application

## Setup Instructions

### Backend

1. Navigate to the `backend` directory.
2. Install dependencies: `npm install`
3. Start the server: `node app.js`

### Frontend

1. Navigate to the `frontend` directory.
2. Install dependencies: `npm install`
3. Start the application: `npm start`

### Database

1. Create a PostgreSQL database named `todo_db`.
2. Create a `tasks` table with the following schema:
   ```sql
   CREATE TABLE tasks (
       id SERIAL PRIMARY KEY,
       description TEXT NOT NULL,
       completed BOOLEAN DEFAULT FALSE
   );

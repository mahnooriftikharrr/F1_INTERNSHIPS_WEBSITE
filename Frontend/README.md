# F1 Internships Website

This is a web application designed to help F1 students find internships that sponsor international students. The project is built using React and Vite for the frontend and Express.js with MySQL for the backend.

## Features

- **Search Internships**: Search for internships by role, company, or title.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Dynamic Data**: Fetch internship data from a MySQL database via an Express.js backend.
- **Routing**: Includes client-side routing using React Router.

## Project Structure

### Frontend
The frontend is located in the `Frontend/` directory and is built with React and Vite.

Key files:
- `src/pages/Home.jsx`: Main page displaying internships.
- `src/pages/cards.jsx`: Component for rendering individual internship cards.
- `src/pages/data.jsx`: Static data for internships (used for testing).
- `vite.config.js`: Vite configuration file.

### Backend
The backend is located in the `Backend/` directory and is built with Express.js.

Key files:
- `server.js`: Express server that connects to a MySQL database and serves internship data.
- `.env`: Environment variables for database configuration.

## Installation

### Prerequisites
- Node.js (v16 or later)
- MySQL database

### Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd F1_Internships_Website

2. Install dependencies for the frontend:
    cd Frontend
    npm install

3. Install dependencies for the backend:
    cd ../Backend
    npm install

4. Configure the backend:
    Create a .env file in the Backend/ directory with the following variables:
    >
    HOST=<your-database-host     
    USER=<your-database-username>
    PASSWORD=<your-database-password>
    DATABASE=<your-database-name>

5. Start the MySQL database and ensure it contains a table named internships - opt_cpt     internships with the required data.

## Running the Application
1. Start the Backend:
    cd Backend
    node [server.js](http://_vscodecontentref_/1)

2. Start the Frontend:
    cd Frontend
    npm run dev

## Scripts
npm run dev: Start the development server.
node server.js: Start the Express server.

## Technologies Used
1. Frontend
React
Vite
React Router
CSS 
2. Backend
Express.js
MySQL
dotenv for environment variable management

## Contact
For any questions or feedback, please contact [iftikhm@plu.edu] || [mahnooriftikharr@gmail.com]
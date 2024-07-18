backend - https://edtestz-ten.vercel.app
Appointment App



This repository contains a full-stack application for managing appointments, built with Node.js, Express, Sequelize, React, and React Router DOM.

Backend Setup
Prerequisites
Node.js installed on your machine
npm (Node Package Manager) or yarn
Getting Started
Clone the repository:

bash
Copy code
git clone <repository_url>
cd appointment-app/backend
Initialize the project:

bash
Copy code
npm init -y
Install dependencies:

bash
Copy code
npm install express sequelize sqlite3 bcryptjs jsonwebtoken dotenv cors
Setup Environment Variables:

Create a .env file in the backend directory with the following content:

plaintext
Copy code
PORT=5000
JWT_SECRET=your_jwt_secret
Replace your_jwt_secret with your preferred JWT secret key for token encryption.

Database Configuration:

Configure Sequelize to connect to your preferred database (SQLite, MySQL, PostgreSQL, etc.). Modify the database configuration in config/db.js accordingly.
Run the Backend Server:

bash
Copy code
node server.js
The server should start running on http://localhost:5000.

Frontend Setup
Prerequisites
Node.js installed on your machine
npm (Node Package Manager)
Getting Started
Navigate to the frontend directory:

bash
Copy code
cd ../client
Initialize the React project:

bash
Copy code
npx create-react-app .
Install dependencies:

bash
Copy code
npm install axios react-router-dom
Setup Environment Variables (Optional):

If your frontend needs environment variables (e.g., API endpoints), create a .env file in the client directory.

Run the Frontend Development Server:

bash
Copy code
npm start
The React development server should start on http://localhost:3000.

Integration and Testing
Ensure that the backend server is running when testing the frontend to enable API requests.
Implement and test authentication flows, booking functionalities, and appointment history display to verify application functionality.

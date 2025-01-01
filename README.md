Charity Management System

The Charity Management System is a web-based application designed to streamline the process of managing charity activities, including registering donors, managing donation workflows, and tracking needy persons' details. It ensures a seamless and efficient experience for both donors and administrators, offering real-time data management and enhanced accessibility.

The project aims to create a transparent and organized system for charity organizations, enabling them to focus on helping those in need.

Features
Donor Registration: Allows donors to register and contribute to various charitable causes.
Needy Persons Management: Tracks and manages details of individuals in need.
Donation Workflow: Simplifies the process of handling donations, from collection to distribution.
Admin Panel: A powerful backend panel for managing users, donations, and workflows.
Responsive Design: Optimized for seamless use across devices.
Technologies Used
Frontend: React JS, HTML, CSS, Bootstrap
Backend: Node JS, Express JS
Database: MongoDB
Styling: CSS, Bootstrap

Setup Instructions
Prerequisites
Ensure the following software is installed on your local machine:

Node.js (LTS version)
MongoDB (Local or Cloud setup)
Git
Installation Steps
Clone the Repository
Open your terminal and run the following command:

git clone https://github.com/Yasirnmn/charity-management-system.git
cd charity-management-system
Install Dependencies
Navigate to the root of the project and install dependencies for both the frontend and backend:

# For backend
cd backend
npm install

# For frontend
cd ../frontend
npm install
Set Up Environment Variables
Create a .env file in the backend directory and add the following environment variables:

PORT=5000
MONGO_URI=mongodb://localhost:27017/charity-db
JWT_SECRET=your_jwt_secret
Run the Application
Open two terminals:

Terminal 1: Start the backend server:
cd backend
npm start
Terminal 2: Start the frontend development server:
bash

cd frontend
npm start
Access the Application
Open your browser and navigate to:
Frontend: http://localhost:3000
Backend: http://localhost:5000

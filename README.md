# Community Problem-Solving Board

A web platform designed to help communities report, prioritize, and track local issues in a transparent and structured way.

## Features

- **User Module**: Report issues with title, description, and optional images
- **Voting System**: Upvote urgent issues to prioritize community needs
- **Admin Dashboard**: Manage and update issue status (Pending, In Progress, Resolved)
- **Timer Module**: Track how long issues remain unresolved
- **Feedback System**: Rate and comment on resolved issues
- **Responsive Design**: Built with Tailwind CSS for seamless user experience

## Technology Stack

- **Frontend**: HTML5, Tailwind CSS, JavaScript
- **Backend**: MERN Stack (MongoDB, Express.js, React, Node.js)
- **Database**: MongoDB
- **Tools**: VS Code, Git & GitHub

##  Installation

1. Clone the repository:
   git clone https://github.com/your-username/community-problem-solving-board.git
Navigate to the project directory:


cd community-problem-solving-board
Install dependencies for both frontend and backend:


# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
Set up environment variables:

Create a .env file in the backend directory

Add your MongoDB connection string and other necessary variables

Run the application:


# Start backend server (from backend directory)
npm start

# Start frontend development server (from frontend directory)
npm start
Open your browser and navigate to http://localhost:3000

# Modules Overview
User Module: Report, view, and vote on issues

Admin Module: Manage issues, update statuses, and monitor progress

Voting Module: One-vote-per-user system with ranking

Timer Module: Tracks issue duration and highlights overdue items

Feedback Module: Post-resolution ratings and comments

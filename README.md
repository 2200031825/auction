Online Auction System

The Online Auction System is a full-stack web application that allows users to participate in auctions by placing bids on listed items. Administrators can add items, manage bidding, and declare winners. The project demonstrates frontend–backend integration, RESTful APIs, authentication, and MySQL database operations.

Features
User Features



User registration and login

View all auction items

Place bids on items

View highest bid for each item

View auction results

Admin Features

Admin login

Add new auction items

Update or delete items

Manage bidding timeline

Declare auction winners



Tech Stack
Frontend



React.js

HTML

CSS

Axios




Backend

Node.js

Express.js

JWT authentication

Database

MySQL




Tools

VS Code

Postman

Git and GitHub




Project Overview

This application simulates an online auction environment where users can compete by placing bids. The admin controls the items available for bidding and the auction timings. The system follows a modular structure with separate layers for frontend, backend, and database interactions using REST APIs.




Architecture

Frontend: React.js application

Backend: Node.js + Express server

Database: MySQL

Communication: REST API using Axios



Flow:
React (Client) → Express (Server) → MySQL (Database)




Project Structure
auction/
   client/        // React frontend
   server/        // Node.js backend
   routes/
   controllers/
   models/
   config/
   README.md


   

How to Run the Project Locally

Clone the repository

git clone https://github.com/2200031825/auction





Install backend dependencies

cd server
npm install




Install frontend dependencies

cd ../client
npm install





Start the backend server

npm start



Start the frontend development server

npm start


Purpose of the Project

This project demonstrates practical skills in:

Full-stack application development

Building and consuming REST APIs

User authentication with JWT

SQL database design and integration

Implementing a functional auction workflow


Online Auction System

This project is a full-stack web application that allows users to participate in online auctions by placing bids on listed items. Admins can add and manage items, control auction timings, and declare winners. The project demonstrates backend APIs, frontend integration, authentication, and database operations.

Features
User Features

User registration and login

View all available auction items

Place bids on items

View highest bid

View auction results

Admin Features

Admin login

Add new auction items

Edit or delete items

Manage bidding timeline

Declare winners

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

Project Overview

The Online Auction System is designed to simulate a real bidding platform where users can compete by placing bids on auction items. The admin is responsible for managing the items and controlling the bidding process. The project follows a clear separation of frontend, backend, and database layers, connected through REST APIs.

Architecture

Frontend (React)
→ communicates with →
Backend (Node.js + Express)
→ interacts with →
MySQL Database

Project Structure
/auction
   /client        (React frontend)
   /server        (Node.js backend)
   /routes
   /controllers
   /models
   /config
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


Start backend

npm start


Start frontend

npm start

Purpose of the Project

This project was created to demonstrate skills in:

Full-stack development

REST API creation

User authentication

SQL database integration

Building a functional working application

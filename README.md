# Flask Application with Comments, Upvotes, and Downvotes
# Structure Your Flask Application
farm_wise/
├── main.py
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── comments.html
│   ├── farmerdetails.html
│   ├── agroproducts.html
│   ├── addagroproducts.html
│   ├── triggers.html
│   ├── farming.html
│   ├── edit.html
├── static/
│   └── uploads/
└── farmers.sql
## Introduction

This is a Flask web application that allows users to register, log in, and interact with posts by commenting, upvoting, and downvoting comments. Users can also reply to comments, edit, and delete them. The application uses a MySQL database to store user information, posts, comments, and votes.

## Features

- User Authentication (Sign up, Log in, Log out)
- Post Creation with Image Upload
- Commenting System with Nested Replies
- Upvote and Downvote Functionality for Comments
- Edit and Delete Comments
- Local Storage for Comment State Management

## Setup Instructions

### Step 1: Set Up Your Environment

1. **Install Required Packages:**
   Ensure you have Python and MySQL installed on your system. Then, install the required Python packages:

   ```bash
   pip install Flask Flask-SQLAlchemy Flask-Login mysqlclient
Configure Your MySQL Database:

Start your MySQL server.

Create a database named farmers:CREATE DATABASE farmers;
Import Your SQL Dump:

Import the provided farmers.sql file into your farmers database:
mysql -u root -p farmers < path/to/your/farmers
## Usage
Open a web browser and go to http://localhost:5000.
Sign up for a new account or log in if you already have an account.
Use the navigation to manage farmer details and post comments.
Technologies Used
Python
Flask
SQLite
HTML/CSS
JavaScript

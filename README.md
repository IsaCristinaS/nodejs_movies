# Project Backend RocketSeat - Movies
## Description
An application was built to save favorite movies associated with tags. The user can create and update their login information. Movie notes can be created, displayed, and deleted. Tags are automatically associated when creating notes and are deleted in cascade.
This project is built using NodeJS and the Express framework. It includes tools for development and testing, such as NodeMon and Insomnia, and a SQLite database managed with Knex migrations and BeeKeeper. 
Password encryption is handled using BcryptJS.

## Technologies
- NodeJS: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- Express: A fast, unopinionated, minimalist web framework for Node.js.
- NodeMon: A utility that monitors for any changes in your source and automatically restarts your server.
- Insomnia: A powerful HTTP and GraphQL client used for testing APIs.
- SQLite: A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- Knex.js: A SQL query builder for PostgreSQL, MySQL, MariaDB, SQLite3, and Oracle.
- BeeKeeper: A database management tool for SQLite.
- BcryptJS: A library to help you hash passwords.
  
## Setup
### Prerequisites
Make sure you have Node.js and npm installed. You can download them from Node.js official website.

## Installation
Clone the repository.
The server should now be running at http://localhost:3000.

## Testing
Use Insomnia or any other API client to test the endpoints.

## Database Management
Manage your SQLite database using BeeKeeper.

## Password Encryption
Passwords are encrypted using BcryptJS before being stored in the database.

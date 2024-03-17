# E-Commerce Back End

## Description

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

## Demo

<a href="https://drive.google.com/file/d/1gOAp2yVDs7bU3JIxLvVFekpulPHknNrQ/view?usp=drive_link">E-Commerce Backend Demo Vid</a>

## Installation

In order for this application function properly you must have dotenv, sequelize, express, and mysql2 installed. Create a .env file with your MySQL database login in. Include the .env file in your .gitignore exclusions to protect your sensitive info. In your mysql terminal, create your database by entering CREATE DATABASE ecommerce_db. Once, database is created switch to it by entering USE ecommerce_db. Quit mysql. Lastly, enter "npm run seed" in the terminal. Now that the data is seeded, run "npm start" to initiate application.

## Usage

Use Insomnia to test RESTful API implementation with HTTP methods POST, GET, GET by id, PUT and DELETE by id. Enter localhost:3001 in the Insomnia command line to connect to server. Use the endpoints "/api/categories", "/api/products", and "/api/tags" to access each table.

## Credits

The starter code was provided by Wash U in Saint Louis Coding Bootcamp. I wrote the rest of the code with the help of Stack Overflow, W3Schools, and the coursework provided. 

## User Story

As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies

## Acceptance Criteria

GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file

THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands

THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application

THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia for categories, products, or tags

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia

THEN I am able to successfully create, update, and delete data in my databaseGIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file

THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands

THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application

THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia for categories, products, or tags

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia

THEN I am able to successfully create, update, and delete data in my database

## Contact Me

Email: [devinjl665@gmail.com](mailto:devinjl665@gmail.com?subject=[GitHub]%20Source%20Han%20Sans)
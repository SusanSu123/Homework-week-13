# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Overview

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.

## How to install

* git clone https://github.com/SusanSu123/Homework-week-13.git
* npm install pakages from pakage.json
* create .env file
* create DB in MySQL Workbench
* node seeds/index.js run seeds DB
* npm start
* use postman/insomnia to test routes 
  on http//:localhost:3001/
* walkthrough video https://www.youtube.com/watch?v=1scY4B8Fu_k

## Prequisites

*  Javascript
*  Express
*  Node.js
*  MySQL
*  NPM

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```


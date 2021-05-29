# E-Commerce

## Project Description

Aa a manager at an internet retail company
I want a back end for my e-commerce website that uses the latest technologies
so that my company can compete with other e-commerce companies

## User Story Criteria

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

## Procedure for Running Code

1.  Copy and past the data base script into MySQL workbench. Go to directory db>schema.sql. Make sure to run the script in MySQL and check to see that a database is created.

2.  Make sure all dependencies are download by checking the package.json folder and running npm i.

3.  Copy seed dat into MySQL tables by running the following prompt in terminal:

        npm run seed

4.  Start connection to server by running the following prompt in the terminal:

        node server.js

5.  To view the data go to the browser and type in http://localhost:3001/api/categories, http://localhost:3001/api/products, or http://localhost:3001/api/tags

## Links

Link to walk through video:
Part 1 - chrome-extension://mmeijimgabbpbgpdklnllpncmdofkcpn/app.html#/files/9000408c-c18d-40a2-y346-8d56e935710c
Part 2 - chrome-extension://mmeijimgabbpbgpdklnllpncmdofkcpn/app.html#/files/cf9b6c73-2501-4ab8-ybe1-f631b70a3376

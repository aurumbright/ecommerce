# E-Commerce Back End

## Description
This project covers the back end for an e-commerce site by modifying starter code. It includes GET, POST, PUT, and DELETE routes for Products, Tags, and Categories for an e-commerce site.

This application uses Express.js, Sequelize, dotenv, and a MySQL database.

## Mock-Up

The walkthrough video shows the GET, POST, PUT, and DELETE routes. [Click here to view the full video.](https://drive.google.com/file/d/1zLU0W5AiMjxaj18uwM2e9FxAD1eTw9iZ/view?usp=sharing) The following gif shows the first GET route.

![A short gif showing the application being tested in Insomnia.](./Assets/ecommerce.gif)


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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

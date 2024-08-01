# 13-E-Commerce-Back-End

## Table of Contents
* [Description](#description)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation & Usage](#installation--usage--tests)
* [Project Demo](#project-demonstration)
* [Links](#links)

## Description
This week we will be building a back-end system for an e-commerce site by modifying starter code. We will be completing that by working Express.js API to use Sequelize to interact with a PostgreSQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the PostgreSQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation & Usage
run `npm i` to install all dependecies
run `npm run seed` to seed data to my database so that I can test my routes
run `npm start` to run code 

## Project Demo
![Project Demo](./assets/13-ECommerce-Back-End.gif)

## Links
Repo: https://github.com/thernand09/13-E-Commerce-Back-End
Video: https://github.com/thernand09/13-E-Commerce-Back-End/blob/main/assets/13-ECommerce-Back-End.gif
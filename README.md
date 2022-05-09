# Slim's E-Commerce Backend

## Table Of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation Method](#installation-method)
- [Link To Video Demonstration](#link-to-video-demonstration)
- [Contributions](#contributions)

## Description

An e-commerce website's backend application utilizing Express.js, MySQL, & Sequelize as the ORM for the SQL models. This app uses REST API routes to make requests and make updates to the database.

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
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

## Installation Method

Run the following commands prior to using the application:

- Please clone this repository or copy the code to your development environment.
- You must have Node.js and MySQL installed on your machine to use this application.

- From MySQL run commands `source db/schema.sql` from the `develop` directory, then `use ecommerce_db`. Finally, run the `quit` command to exit MySQL.

- From the `develop` directory run commands:

```
npm i
```

```
npm start
```

## Link to video demonstration

<a href='https://drive.google.com/file/d/19NlBvpr4HdrEFK21ei0c2BrdDj-Q19Pt/view'>Video Demonstration</a>

## Contributions

<a href='https://github.com/ShuanLim'>Shuan Lim</a>

Contact me via <a href='shuanmlim@gmail.com'>email</a>

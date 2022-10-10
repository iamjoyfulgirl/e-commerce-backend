# ORM E-Commerce Backend

## Description

This is a MySQL2 database and backend application for an e-commerce site. Built using MySQL2, Express, and Sequelize.

## Below are GIFs showing the functionality of the application: 📽

![DB Setup and DB Seed](./assets/DB%20Setup%20and%20Seed.gif)

![Start Server](./assets/App%20start%20server.gif)

![GET All](./assets/GET%20All.gif)

![GET All by ID](./assets/Get%20By%20ID.gif)

![POST PUT DELETE Products and Tags](./assets/POST%20PUT%20DELETE%20Products%20%26%20Tags.gif)

![POST PUT DELETE Categories](./assets/POST%20PUT%20DELETE%20Categories.gif)

🎥 The full-resolution recordings showing the full functionality of the application are separated, and can be viewed from the following links:

[DB Setup and DB Seed (full resolution)](https://drive.google.com/file/d/1CRtx0If1YxWdvh1V9iQbRnZ7amQrB2oH/view)

[Start Server (full resolution)](https://drive.google.com/file/d/1x0mG8y5j1TuYVEX6MtnQWm2MWwwQzbVG/view)

[GET All (full resolution)](https://drive.google.com/file/d/1UNVVCUm3yv8Nwmt1JJB1srFuNdlpIgQH/view)

[GET All by ID (full resolution)](https://drive.google.com/file/d/1vD7WFPOl9Fgh86xhFEzcOJ8WkkclAF4L/view)

[POST PUT DELETE Products and Tags (full resolution)](https://drive.google.com/file/d/1EbVAQnx9F2UQoB-58KN280xJ0o79-DG7/view)

[POST PUT DELETE Categories (full resolution)](https://drive.google.com/file/d/1PKPm0SJtHOsx4pZzb-Q3cj0evrPb5gG9/view)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## Installation

In the terminal, in the root of the project run `npm i` to install the application's dependencies.

## Usage

Note: This project assumes that you have MySQL2 installed.
Run the following commands in the terminal, in the root of your project, and answer the prompted questions:

👩🏻‍💻

`mysql -u root -p`

Enter your password when prompted for your password

`source db/schema.sql`

`quit`

`npm run seed`

`npm start`

Once the server is running, you can open Insomnia and make calls to the Products, Categories, and Tags APIs.

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

## Questions?

Questions about this project can be directed to:

- Email: sherri.a.knight@gmail.com.
- You can view more of my projects at https://github.com/iamjoyfulgirl

## License

![badge](https://img.shields.io/badge/license-MIT-brightgreen)
<br />  
Content in this project is covered by the MIT license.

---

ORM E-Commerce Backend - Copyright 2022 Sherri Knight

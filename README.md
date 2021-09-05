# E-Commerce Back End

## Description

This is the back end for an e-commerce site. This Express.js API uses Sequelize to interact with a MySQL database.

[Github Repository](https://github.com/s-cabrera/E-Commerce-Back-End)

## Table of Contents 
* [User Story](#userstory)

* [Technology](#technology)

* [Installation](#installation)

* [Usage](#usage)

* [Demo](#demo)

* [Questions](#questions)

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Technology
  * [MySQL2](https://www.npmjs.com/package/mysql)
  
  * [Sequelize](https://www.npmjs.com/package/sequelize)
  
  * [dotenv](https://www.npmjs.com/package/dotenv) package

## Installation 

To install necessary dependencies, run the following command:
```bash
npm install
```

## Usage

In the MySQL shell, copy and paste the contents of the /db/schema.sql folder (as shown below) and run it

```bash
-- DROP DATABASE
DROP DATABASE IF EXISTS ecommerce_db;

-- CREATE DATABASE
CREATE DATABASE ecommerce_db;
```
Now that the database exists, seed it with the following command on your VS Code bash terminal: 

```bash
npm run seed
```

Last step, start the server. Run the following command in the VS Code bash terminal:

```bash
npm start
```

Now you can make requests to your server!

## [Demo](https://drive.google.com/file/d/1b9UrngUzqPjFB2z6fjByYTp_Jkuzo5U6/view)

![Walkthrough Video](https://github.com/s-cabrera/E-Commerce-Back-End/blob/main/assets/demo.mp4)

## Questions

If you have any questions about the repo, open an issue or contact me directly at stephanie.cabrera.333@gmail.com. You can find more of my work at my [Github](https://github.com/s-cabrera/).

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

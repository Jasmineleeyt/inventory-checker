# Inventory Checker

## Description
An application that manages the back end of an e-commerce site.

## Table of Contents
- [Description](#description)
- [Installations](#installations)
- [Usage](#usage)
- [Demo](#demo)
- [Credits](#credits)
- [License](#license)

## Installations
:computer: To run this locally, please make sure you have the following:

:heavy_check_mark: [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

:heavy_check_mark: [Node.js](https://nodejs.org/en)

:heavy_check_mark: [Express](https://www.npmjs.com/package/express)

:heavy_check_mark: [MySQL2](https://www.npmjs.com/package/mysql2)

:heavy_check_mark: [Sequelize](https://www.npmjs.com/package/sequelize)

:heavy_check_mark: [dot.env](https://www.npmjs.com/package/dotenv)

## Usage
Using the query provided in schema.sql, create a database in MySQL Workbench. Then, seed the database by typing ```npm run seed``` in the terminal and run the command ```node server.js``` to start the server. Hit the endpoints as specified under the routes folder and the user should be able to perform the CRUD operations on the data stored in the ecommerce_db database.

## Demo
[inventory-checker.webm](https://github.com/Jasmineleeyt/inventory-checker/assets/140264009/d497a88c-637d-42a1-9556-df07645251c8)

## Credits
Starter code from [coding-boot-camp](https://github.com/coding-boot-camp/fantastic-umbrella)

Documentations that helped understand the syntax of the queries and the declaration of the associations:

- [Sequelize Model Querying](https://sequelize.org/docs/v6/core-concepts/model-querying-basics/)

- [Sequelize Associations](https://sequelize.org/docs/v6/core-concepts/assocs/)

- [Sequelize Advanced M:N Associations](https://sequelize.org/docs/v6/advanced-association-concepts/advanced-many-to-many/)

## License
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
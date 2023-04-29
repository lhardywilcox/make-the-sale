# make-the-sale

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

make-the-sale is the back-end construction for an e-commerce website.  It includes a relational database with tables that share data to link categories, products and tags.  It also includes the routes required to get data from the tables, as well as create, update and delete data from the tables.

This project taught me a lot about organizing the background structure of databases, and how to access the information from the server.  I learned what routes were needed and how to test them. The biggest challenge for me is understanding fully how to get the tables to relate to each other, and how to retrieve the specific information I am interested in.

## Table of Contents

-[Installation](#Installation)

-[Usage](#Usage)

-[Credits](#Credits)

-[License](#License)

-[Tests](#Tests)

-[Questions](#Questions)

## Installation

This project uses the following technologies: mysql, node.js, npm, express, sequelize, dotenv.

The database was built using mysql, and seeded using Sequelize.  Routes were coded in Javascript and tested with Insomnia.

A video demonstration of the project:

[make-the-sale](https://watch.screencastify.com/v/jUWfaFV4ucotSFtNgJWV)

## Usage

To use make-the-sale, from the command line interface, log into mysql and run SOURCE db/schema.sql.  Then exit mysql and type "npm run seed" to run the script that seeds the database.  After the database is seeded, use "npm start" to start the server.
 
## Credits

I referred to the class exercises and documentation to help me develop the routes.  The starter code is ©2023 EdX bootcamps.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 
[MIT License](https://opensource.org/license/mit-0/)
 
For the complete text of the license, please click on the link provided.

## Tests

All routes were tested using Insomnia.

## Questions

If you have questions, please reach out to me at:

[github profile](github.com/lhardywilcox)

or

[email](motacycaryda@mac.com)

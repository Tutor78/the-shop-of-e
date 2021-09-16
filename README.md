# The Shop of E

![badmath](https://img.shields.io/badge/License-MIT-informational)

## Description

The backend for an ecommerce website that is built to allow users to perfrom CRUD operations against a database of products, tags, and categories. This project is a standalone application that can be run from your computer and queried using api testing software.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Languages](#languages)

## Installation

1. ```git clone``` the files to your computer
2. Navigate to the root directory that houses the files and run ```npm install```
3. Create a .env file that contains the following:
    > DB_NAME='ecommerce_db'
    >
    > DB_USER='your db username'
    >
    > DB_PW='your db password'
4. From the command line run ```npm run seed``` to seed the database.

## Usage

After the database has been seeded, navigate to the command line and run ```npm start```. This will start the server which will listen for post 3001. After the server has been started, open up your api testing software of choice and run operation against the database. [This](https://drive.google.com/file/d/1xNaX1ozZJ4ugBl4xLLPR8ypE9zXW6IUH/view) video contains a demonstration walkthrough of the various endpoints using Postman.

## License

This project is licensed under the [MIT](LICENSE) license.

## Languages

* Javascript
    * node.js
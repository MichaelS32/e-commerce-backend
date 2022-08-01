# e-commerce-backend

## Description
E-commer database and app back-end that uses mysql2, Sequelize, Express, and dot env to allow users the ability to perform CRUD operations on database objects.

## Demo


## Installation
1. "git clone" the repository onto your local machine.
2. From the root of the repository run "npm init".
3. Now install the packages "npm install mysql2", "npm install sequelize", "npm install dotenv"

## Usage
To use the database and test the back-end routes using insomnia first access create the database. Run "mysql -u root -p" enter your password for my sql. Run "npm source db/schema.sql" this will remove a db by the same name if there was one if not it will just create a new ecommerce_db. run "quit" to exit mysql. Next type "npm run seed" this will populate your database with the seed information. Now run "npm start" this will establish a connection to the server and allow you to test the endpoints.

## Links
[Github Repository:](https://github.com/MichaelS32/e-commerce-backend)

## Contributors
[MichaelS32](https://github.com/MichaelS32)

## License
Please visit the link for detailed information on this license.

  [MIT](https://www.mit.edu/~amini/LICENSE.md)
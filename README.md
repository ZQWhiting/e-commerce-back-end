# E-commerce Back End
![license](https://img.shields.io/badge/License-ISC-blue)

<a name='description'></a>
## Description
This project is the back end for an e-commerce website. It uses Express.js and Sequelize to interact with a MySQL database.

## Table of Contents
* [Description](#Description)
* [Prerequisites](#Prerequisites)
* [Installation](#Installation)
* [Usage](#Usage)
* [License](#License)
* [Contributing](#Contributing)
* [Tests](#Tests)
* [Questions](#Questions)
* [Credits](#Credits)

<a name='Prerequisites'></a>
## Prerequisites:
* [Node](https://nodejs.org/en/)
* [MySQL](https://www.mysql.com/)

<a name='installation'></a>
## Installation:
1. Clone the repository.
2. Navigate to the repository in the terminal and run `npm i`.
3. Enter the database name and your mysql user and password in the `.env` file. If no .env file exists, create it in the root of the repository and enter the following information:
```
DB_NAME='ecommerce_db'
DB_USER='yourMySQLuser'
DB_PW='yourMySQLpassword'
```
4. To create the database, run `npm run schema` in the terminal and enter the password for your MySQL user 'root' (user can be changed in package.json scripts).
5. (Optional) Populate the database with test data with the command `npm run seed`.
6. (Optional) In the MySQL Shell, create a new mysql user with permissions on the database, and update the `.env` file:
    ```
    mysql> CREATE USER 'user'@'localhost' IDENTIFIED BY 'some_pass';
    mysql> GRANT ALL PRIVILEGES ON ecommerce_db.* TO 'user'@'localhost';
    ```

7. Run `npm start` in the terminal to run the server.

<a name='usage'></a>
## Usage
[Walkthrough Video](https://youtu.be/rE0WAeie1BQ)
* Run the server in the terminal using `npm start`.
* Test the routes using [Insomnia Core](https://insomnia.rest/) or other API testing software.

<a name='license'></a>
## License
Licensed under the [ISC](./docs/LICENSE.txt) license.

<a name='contributing'></a>
## Contributing
[Contributor Covenant](./docs/contributor-covenant.txt)

<a name='questions'></a>
## Questions
Reach me at my github or email!

[GitHub](https://github.com/ZQWhiting)

<zach.whiting@icloud.com>

<a name='credits'></a>
## Credits
Developed by Zachary Q. Whiting (ZQWhiting).
Starter code provided by the University of Utah Online Coding Bootcamp.

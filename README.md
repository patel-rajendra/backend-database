# E-commerce Back End Starter Code

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [Demo](#Demo)
- [License](#License)

##

## Description

This back end node application uses the Sequelize to interact with a MySQL database and allowing users to perform CRUD operations. 

## Installation

1. To install application, clone the main project via the HTTP or SSH link on github.

```
git clone
```

2. Once cloned, open up the project folder in your text editor and run the following command in terminal to install all dependencies.

```
npm install
```

## Usage

# Initial setup

Create a '.env' file in the main directory path and include the following data:

```
DB_NAME='your_database_name'
DB_USER='your_mysql_username'
DB_PW='your_mysql_password'
```

Once your '.env' has been created with the corresponding data, open up the schema ('db/schema.sql') and update the database label to match with the database you included in your '.env' file.

# Schema setup

If you'd like to build the schema, you can enter the MySQL shell by typing in terminal:

```
mysql -u root -p
```

After entering your password followed the following command:

```
source db/schema.sql
```

To seed the database type this command in terminal:

```
npm run seed
```

To start the server, type in terminal:

```
npm start
```

## Demo

Demo video of execution:
[View here](https://www.screencast.com/t/lCm2S09MXrwk)

## Built With

- Node.js
- Express.js
- Sequelize
- Dotenv
- MySQL2
- JavaScript

## License

This project is covered under the MIT License.

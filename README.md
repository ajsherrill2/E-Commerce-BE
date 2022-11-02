# E-Commerce-BE

## Description

In this Project I created the back end for an e-commerce site. I configured a working Express.js API to use Sequalize to interact with a MySQL database. Using Insomnia on an express server to reach endpoints for each CRUD operation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Badges](#Badges)
- [Features](#Features)
- [Questions](#Questions)

## Installation

To Install:

Install node.js lts

Clone the repository from GitHub (https://github.com/ajsherrill2/E-Commerce-BE).

Run these command lines in your terminal to install necessary dependencies:

```
npm init -y
npm install
```

Additional installations (sequalize, mysql2, and dotenv)

```
npm i sequalize
npm i mysql2
npm i dotenv
```

Please Run "SOURCE db/schema.sql;" atleast once in your MySQL terminal.

```
mysql -u root -p
-SOURCE db/schema.sql;
```

Please change ".env.EXAMPLE" to ".env" and provide personal DB_PASSWORD, DB_NAME and DB_USER.

## Usage

Direct your terminal to the repository root directory and run this command line to initiate application:

```
npm seed
```

Then

```
npm start
```

Watch this short video demonstration [here](https://drive.google.com/file/d/1kGyH8wRyRzWgudFnwCmS7hVx70I-CdDv/view)

## License

This application is covered under the MIT license.

## Badges

![license](https://img.shields.io/badge/license-MIT-yellow.svg)

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

![badmath](https://img.shields.io/github/repo-size/ajsherrill2/E-Commerce-BE)

## Features

Features you will find in this app include:

- GET, POST, PUT, and DELETE operations for one to many and many to many relationships

## Questions

If you have any questions about the repo open an issue or contact me directly at adamsherrill2@gmail.com. You can find more of my work at [ajsherrill2](https://github.com/ajsherrill2/).


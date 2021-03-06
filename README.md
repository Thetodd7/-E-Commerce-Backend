# E-Commerce Backend [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Screenshot

![Screen Shot 2021-09-07 at 1 20 59 PM](https://user-images.githubusercontent.com/85806673/132385681-83156a1a-1b94-4ad9-aab8-c486ed666152.jpg)

## Video
https://youtu.be/in9M5KVx3Jc


## Description

An E-Commerce backend app that utilizes Node.js, Sequelize, and Express.js. This app creates custom API endpoints which allow the user to create, read, update, and delete from the E-Commerce MySQL database. The database contains information about the products that the site will sell. The product information is compartmentalized in related tables within the database which were created using the ORM Sequelize.

## Table of Contents

- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [Tests](#Tests)
- [License](#License)
- [Collaboration](#Collaboration)

## Installation

### Dependencies: **Requires** **_Node.js_** installed on your computer

\
To install the npm dependencies cd into the main directory and run:

```
npm i

cd db && mysql -u root -p

source schema.sql

exit

cd..

npm run seed
```

## Usage





To use this node app, clone the repo down, use the terminal to cd into the root directory. Then run:

```
npm start
```

Use the terminal and start up the server. You can then access the API endpoints througha web browser or Insomnia.

## Tests

To test please run:

```
npm test
```

## License

[MIT License](https://opensource.org/licenses/MIT)

## Collaboration

Please feel free to collaborate with me on this project. Just download it and submit a well documented pull request.

If you have any questions, please contact me at toddgranados@gmail.com

# E-Commerce Backend

## Table Of Contents
* [About](#about)
* [Technologies](#technologies)
* [Installation](#installation)
* [Contributions](#contributions)
* [Questions](#questions)

## About

This project is a backend application that functions as customizable database for an E-Commerce website using Sequelize in conjunction with a MySQL database. Using Insomnia, the user is able to interact with the backend functions of this app and view categories, tags, products, and adjust them as needed. 

Attached below is an image depicting the application running via Insomnia: 



### Demonstration Video

Attached here is a link to a video demonstration of the application. 


## Technologies
This project was created with: 
* [Javascript](https://www.javascript.com/)
* [Node.js](https://nodejs.org/en/)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Express](https://www.npmjs.com/package/express)
* [Dotenv](https://www.npmjs.com/package/dotenv)

## Installation
First, clone this respository using the following command in your terminal:
<br>
```terminal
git clone git@github.com:Briggoh/E-Commerce.git
```
Verify that Node and MYSQL are downloaded to your computer. This is necessary.  

Install the required dependencies by inputting the following command in the  
```terminal
npm i
``` 
Open up MySQL shell and input the following command: 

- "DROP DATABASE IF EXISTS ecommerce_db;"
- "CREATE DATABASE ecommerce_db;"

Then, seed the data by inputting the following command in your terminal:
```terminal
npm run seed
```
Finally, you may begin running the application by inputting the following command in your terminal: 
```terminal
npm start
```
Utilization of Insomnia is required if the user wishes to view, update, create, or delete different routes. 

## Contributions
Although a 3rd party's interest in helping me is always appreciated, I will not be accepting any contributions for this project.

## Questions
Questions about this repository? Please contact me at [H.E.Briggs99@gmail.com](mailto:H.E.Briggs99@gmail.com). Or, view more of my work in GitHub at [Briggoh](https://github.com/Briggoh).

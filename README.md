# :hamburger: Sequelized Burger
A Sequelize version of my Fancy Burger app, incorporating Node/Express.js/MySQL/Handlebars/ORMs




## Description
When the user inputs a new burger, the burger is inserted into the database.  Burgers are displayed correctly in either "Ready To Eat" or "Devoured" using the built-in Handlebars helpers #each, #if, and #unless.  When the user "eats" a burger, the burger's status is updated from "devoured=false" to "devoured=true".


## Dependencies
* express
* express-handlebars
* body-parser
* method-override
* mysql
* Sequelize
* Material CSS

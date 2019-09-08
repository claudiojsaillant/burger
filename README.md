# burger

# Burger App
This app is deployed on: https://radiant-woodland-57287.herokuapp.com/

Burger app made with mysql, node.js and html/css.

## App Composition
This app in multiple files:

App folders: (./config)Contains the configuration of the db, (./public and views) public contains all the files used by the handlebars (./views), All the express routes configuration (api and html routes are found in ./controllers) and in the model folder (./models)  simplifies all the db querys in the ORM.

server.js: This file launches the app and link all the files together. 

Package: Contains all the modules the app depends on, so the user can install them using npm.

## Technologies used

Html
JavaScript
Node.js
Node Packages: *express *mysql *express-handlebars *dotenv *body-parser

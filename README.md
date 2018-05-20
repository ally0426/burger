# burger

## DB Setup

DB folder is created and schema.sql is added to that foler to write SQL queries:


id: an auto incrementing int that serves as the primary key.
burger_name: a string.
devoured: a boolean.


## Config Setup

Config directory is created and connection.js and orm.js files are added inside that directory so that I can retrieve and store data in my db.

selectAll()
insertOne()
updateOne()


## Model setup

Models directory is created and burger.js is added to that directory to call the ORM function using burger specifi input for the ORM.


## Controller setup

Controllers directory is created and burger_controller.js file is added to that directory to create the router for the app.


## View setup

Views directory is created and index.handlebars is added to have the template rendered. 
Layout directory is created inside Views directory and main.handlebars is added to use handlebars function.


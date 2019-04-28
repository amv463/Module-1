# Docker Node-Mongo Example

The purpose of this example is to create a docker container and run a 
sample application using Node.js and MongoDB.

Simply run `docker-compose up`  to initiate.

## Files

### Dockerfile
- Contains commands to put together the image

### docker-compose.yml
- Defines and configures docker applications  

### index.js 
- Contains model, routes, and set view engine for the application

### package.json
- Bring in dependencies and contains start up script


## Directories

### adr

This directory contains the Architectural Design Records for explaining the 
process of creating the application

### views

- `index.ejs`

This directory contains the file containing the application form to add 
an item and loop through the list of items.


### models

- `Item.js`

This directory contains the files necessary to create the item schema for 
adding items to the list.


### data

This direction contains files used to store and maintain database data.
# Module-1

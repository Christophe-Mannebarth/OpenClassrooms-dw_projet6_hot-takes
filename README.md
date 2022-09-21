# OpenClassrooms - Web Developper - Project6 - HotTakes

## Frontend & Backend - Mannebarth Christophe \_ 09/2022

## Prerequisites:

You will need to have Node (https://nodejs.org/en/) and npm installed locally on your machine.

You must also first create a MongoDB database (https://www.mongodb.com/atlas/database).

## Author's Note:

### To the person who will evaluate this project

Since I made some cosmetic changes to the frontend (indications in the form fields relating to validation constraints)

it is preferable for this demonstration to use the attached frontend rather than the one on the OpenClassrooms github repository.

## Frontend:

### Install & Start

Open a terminal in frontend folder then run the following commands

```
npm i

npm start
```

### To note

_Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files._

## Backend:

### Preparations

Transform the ".env.template" file into an ".env" file by following these guidelines:

    #### Connect to MongoDB ####

    DB_ACCESS = the access to your cluster on MongoDB

    #### Secret Key for the user email encryption (without "#") ####

    EMAIL_KEY = a secret key of your choice for the email

    #### Token key for the user password hashing (without "#") ####

    TOKEN_KEY = a secret key of your choice for the token

    #### Server port ####

    PORT = the port of the backend server (here 3000)

    #### Environment ####

    NODE_ENV = development, testing or production (here development)

### Install & Start

Open a terminal in backend folder then run the following commands

```
npm i

npm start
```

### To note

_The "images" folder will be created automatically when creating your first sauce._

_Default port : `3000` (http://localhost:3000)_

Enjoy

## Fullstack Application Using MongoDB, NodeJs, React and Redux

#### Backend features

The Mongo database was hosted at MLab for convenience.
Gravatar has been implemented for profile photo if user email has an avatar
in wordpress it is automatically saved to the bank.
Sensitive routes were protected through JWT in conjunction with passport.

#### Using

- Nodejs
    * Express
    * Nodemon - To restore the server whenever there is a change.
    * Passport - To protect private routes
    * Jwt - To protect private routes
    \* Bcrypt - To Crypt User Passwords Before Saving to Bank
- MongoDB
    \* Mongoose

#### Frontend features

React was used in conjunction with Redux and React-router to build the SPA.
Protected routes redirect to home and are only accessible through auth.
Localstorage was used to persist user state when reloading pages.

#### Using

- React
    * Redux - To manage application state
    * asyncRoutes - Routes load into chunks, thus preventing the application from getting heavy on a first load.
- Axios - To make HTTP requests
- Native local storage - To persist state and auth on private routes
- MaterialUI components

## How to start the app

#### Requirements

- Node.js
- NPM

### Installing the Packages

Run the command below to install the dependencies:
```bash npm install ```

### Starting the server

Run the command below to start Nodejs and connect to the MongoDB database:
```bash npm run server ```

Wait for execution and the API will be running on Url `http://localhost:8001/api/`

The available endpoints are:

- Post - Login [more](https://documenter.getpostman.com/view/4374482/test-fullstack/RW87p9Mq#0e46cf7d-edf9-416c-bfab-84022d8a346e)
- Post - Register [more](https://documenter.getpostman.com/view/4374482/test-fullstack/RW87p9Mq#db625518-ec7d-41c7-9894-189322033ac6)
- Put - Update Profile [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#ee34ae20-fe46-46f5-8666-7ed784448d65)
- Del - Delete Account [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#1481a07f-160a-4b9c-ba95-7ceb20266b53)
- Get - List Users [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#5f812e40-7bf1-47e8-87bb-1390b2fdf70b)

[Full documentation can be found at Postman](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq)

Leave the server running on one terminal, open another, and proceed to the next step:

### Starting SPA React

To do this just execute the command below, and you're done! : D
```bash npm start ```

The application will start automatically in the browser at Url `http://localhost:3000`

<br/>
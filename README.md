#  React Shift Hours Management System
an employee management and scheduling app that allows… 
* Managers to manage and schedule employees
* Employees to view work schedules
* Front React and Back Typescript

## Backend-API Typescript (Nest)
[backend-api-shift-working](https://github.com/Ketibansapi/react-shift-working-backend)

## Run locally

Schedulr requires [Node.js](https://nodejs.org/) and [MongoDB](https://docs.mongodb.com/manual/installation/) to run

### Installation
Once mongo is installed, open a new terminal and run 


`$ mongod`

Open another terminal window and navigate to project directory and run

`$ npm install`

Create a .env file with and add the code below (not strings)

``` 
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_CALLBACK_URL=http://YOUR_DOMAIN/auth/google/callback
    
LINKEDIN_ID=
LINKEDIN_SECRET=
LINKEDIN_CALLBACK=http://YOUR_DOMAIN/auth/linkedin/callback
```

If you dont want to go through the trouble of creating the API keys, put in dummy numbers/text and the app should still work, however passport social login will not.

### Run App

`$ npm run build`

Wait for webpack to bundle then

`$ npm start`


Open a browser and go to [http://localhost:8080](http://localhost:8080)

## Tech Stack
Built with React, Node (Nest and express), Typescript
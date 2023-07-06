# EPAM NodeJS HW3 - UBER like service for freight trucks

## Project Description: 
Use NodeJS to implement UBER like service for freight trucks, in REST style, using MongoDB as database. This service should help regular people to deliver their merchandise and help drivers to find loads. Application contains 2 roles, driver and shipper.
+ Driver/Shipper are able to register/login to the system, view profile, change password, reset password and delete account.
+ Driver are able to add trucks, view and created truck, update to his truck info, delete and assign him self to the truck.
+ Shipper are able to create loads, view created loads, update load's status, delete load and view shipping info.

## Technologies:
+ ExpressJS
+ MongoDB as database, Mongoose
+ GoogleAPIs, NodeMailer for email sending.
+ JsonWebToken, bcrypt.
+ Joi.
+ MVC Model

## API URL samples:



## .env file format
SECRET_KEY = 
RESET_PASSWORD_KEY = 
DB_CONNECT = 
BASE_URL = 

//GoogleAPIs
CLIENT_ID = 
CLIENT_SECRET = 
REDIRECT_URI = 
REFRESH_TOKEN = 

## How to run app
1. config .env file
2. npm install
3. npm start

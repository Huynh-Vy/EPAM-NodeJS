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


![image](https://github.com/Huynh-Vy/EPAM-NodeJS/assets/87691625/6247dffd-c1db-419c-81e0-2bb15a641c6e)


![image](https://github.com/Huynh-Vy/EPAM-NodeJS/assets/87691625/d8e27e2d-53a7-4edb-a9fc-ba65b66d102a)


![image](https://github.com/Huynh-Vy/EPAM-NodeJS/assets/87691625/dd8d7bd1-e2a8-4cf5-888b-e047057de5e8)


## .env file format
1. SECRET_KEY = 
2. RESET_PASSWORD_KEY = 
3. DB_CONNECT = 
4. BASE_URL = 

## GoogleAPIs
1. CLIENT_ID = 
2. CLIENT_SECRET = 
3. REDIRECT_URI = 
4. REFRESH_TOKEN = 

## How to run app
1. config .env file
2. npm install
3. npm start

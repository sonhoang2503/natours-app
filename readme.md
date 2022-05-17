
# Natours 

### An awesome tour booking site  is specially designed for anyone who love travelling !!

Live demo   : https://natours-hoangnguyen.herokuapp.com


## Key features

* Authentication and Authorization 
  - Login and logout 

* User profile

  - Update username, avatar, email, and password

* Tour
  - Tour details, location, map, users rating and reviews

* Booking
  - Manage booking , create , payment (stripe) , history.

## Demonstration
#### Home Page :
![natoursHomePageonline-video-cutt](https://user-images.githubusercontent.com/58518192/72606801-7ebe0680-3949-11ea-8e88-613f022a64e5.gif)

#### Tour Details :
![tourOverviewonline-video-cutterc](https://user-images.githubusercontent.com/58518192/72606859-a0b78900-3949-11ea-8f0d-ef44c789957b.gif)

#### Booking and Payment process :
![paymentprocess-1-ycnhrceamp4-7fW](https://user-images.githubusercontent.com/58518192/72606973-d9eff900-3949-11ea-9a2e-f84a6581bef3.gif)


## Main Tools And Technologies 

* Html, css, javascript
* Nodejs, expressjs , mongodb, pug, jwt, stripe, nodemailer, sendgrid.

## Installation
You can fork the app or you can git-clone the app into your local machine. Once done that, please install all the
dependencies by running
```

$ npm i
!Set up your env variables 
$ npm run watch:js
$ npm run build:js
$ npm run dev (for development)
$ npm run start:prod (for production)
$ npm run debug (for debug)
$ npm start
```
### Setting Up Your Local Environment
* In your .env file, set environment variables for the following:


```
    * DATABASE=your mongodb database url
    * DATABASE_PASSWORD=your mongodb password

    * SECRET=your json web token secret
    * JWT_EXPIRES_IN=90d
    * JWT_COOKIE_EXPIRES_IN=90

    * EMAIL_USERNAME=your mailtrap username
    * EMAIL_PASSWORD=your mailtrap password
    * EMAIL_HOST=smtp.mailtrap.io
    * EMAIL_PORT=2525
    * EMAIL_FROM=your real life email address

    * SENDGRID_USERNAME=apikey
    * SENDGRID_PASSWORD=your sendgrid password

    * STRIPE_SECRET_KEY=your stripe secret key
    * STRIPE_WEBHOOK_SECRET=your stripe web hook secret
```


## Acknowledgement

* This project is part of the online course  [Node.js, Express, MongoDB & More: The Complete Bootcamp ] i have taken. Thanks to Jonas Schmedtmann for creating this awesome course!

* The app is actually quite more complex than it is indicated in this documentation. Nevertheless, this summary is enough to help you understand the major features of the app.

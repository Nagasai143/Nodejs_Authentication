# NodeJS Authentication App
> A complete authentication app with login, logout, register, forget password, email verification(for added security), and access control. Can be used as starter for other Node.JS applications. using Node.js, Express, Passport, JWT, Mongoose, and more. 

**Starting Page:**

![Screenshot (4)](https://user-images.githubusercontent.com/49118089/90341145-b776a900-e01a-11ea-93c8-4f6864a141c1.png)

**Register for New User:**

![register](https://github.com/Nagasai143/Nodejs_Authentication/assets/61235918/372b7858-5591-4d9c-b80d-b1b777952553)

**login:**

![login](https://github.com/Nagasai143/Nodejs_Authentication/assets/61235918/f38ae505-7361-4898-8025-63e04145678c)


**Dashboard:**

![dash](https://github.com/Nagasai143/Nodejs_Authentication/assets/61235918/cd2b463b-9555-45f5-84b3-758f45856a27)

**logout:**

![logout](https://github.com/Nagasai143/Nodejs_Authentication/assets/61235918/2b7c4e5b-e753-4884-9828-576e427bf1dc)

**Forgot Password:**

![forgot_password](https://github.com/Nagasai143/Nodejs_Authentication/assets/61235918/cdc52ff2-658c-482f-97c6-e7ba77a5f080)

## Technologies Used
1.  NodeJS
2.  Express
3.  EJS
4.  MongoDB
5.  Mongoose
6.  PassportJS
7.  JWT
8.  Nodemailer


## Prerequisites
- Git
- NodeJS
- CLI



##### Installing NPM dependencies

`npm install`

##### Then simply start your app

`npm start`

#### The Server should now be running at http://localhost:8000/

## Folder Structure

nodejs-auth <br>
├── assets <br>
│ --- ├── secure-icon.png <br>
│ --- ├── cyber-security-icon.jpg <br>
│ --- └── css <br>
│ -------- └── bootstrap.min.css <br>
├── config <br>
│ --- ├── checkAuth.js <br>
│ --- ├── key.js <br>
│ --- └── passport.js <br>
├── config <br>
│ --- └──authController.js
├── models <br>
│ --- └── User.js <br>
├── node_modules <br>
├── routes <br>
│ --- ├── auth.js <br>
│ --- └── index.js <br>
├── views <br>
│ --- ├── dash.ejs <br>
│ --- ├── forgot.ejs <br>
│ --- ├── layout.ejs <br>
│ --- ├── login.ejs <br>
│ --- ├── messages.ejs <br>
│ --- ├── register.ejs <br>
│ --- ├── reset.ejs <br>
│ --- └── welcome.ejs <br>
├── .gitignore <br>
├── package.json <br>
├── package-lock.json <br>
├── README.md <br>
└── server.js <br>

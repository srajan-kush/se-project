<h1 align="center">
CineVerse
</h1>
<p align="center">
MongoDB, Expressjs, React/Redux, Nodejs
</p>

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE) [![npm version](https://img.shields.io/npm/v/react.svg?style=flat)](https://www.npmjs.com/package/react) 

CineVerse is an online Movie Ticket Booking web app with MERN Stack.

  - Online Booking System
  - Admin Dashboard
  - Dark Theme UI


> MERN is a fullstack implementation in MongoDB, Expressjs, React/Redux, Nodejs.

MERN stack is the idea of using Javascript/Node for fullstack web development.

<img src="https://github.com/TechKumarNitish/image/blob/main/mern.png" />

# Features!

  - Add / Update / Delete Movies
  - Add / Update / Delete Cinemas
  - Add / Update / Delete Showtimes
  - Add / Update / Delete Reservations
  - Add / Update / Delete Users
  - Generate QR Code for reservation check in
  - Send HTML emails invitations 


You can also:
  - Export QR Code pass as PDF

### Tech
CineVerse uses a number of open source projects to work properly:
* [MongoDB](https://www.mongodb.com/) - A document-oriented, No-SQL database used to store the application data.
* [ExpressJS](https://expressjs.com/) - fast node.js network app framework.
* [ReactJS](https://reactjs.org/) - A JavaScript library for building user interfaces.
* [Redux](https://redux.js.org/) - A predictable state container for JavaScript apps.
* [nodeJS](https://nodejs.org/) - A JavaScript runtime built on Chrome's V8 JavaScript engine

### Installation

CineVerse requires [Node.js](https://nodejs.org/)  to run.

Set environment variables 

```sh
$ Create a .env file in your server and client folder
$ See the .env sample
create a mongodb database and add your connection string into .env file
```
## Environment Variables

The following environment variables are required for the application to function correctly.  

| Variable        | Required | Description                        |
|----------------|----------|------------------------------------|
| `MONGODB_URI`  | ✅ Yes   | MongoDB connection string         |
| `MAIL_HOST`    | ✅ Yes   | SMTP mail server host             |
| `GMAIL_USER`   | ✅ Yes   | Gmail user email for SMTP         |
| `GMAIL_PASSWORD` | ✅ Yes | Gmail app password for SMTP       |
| `CLOUDINARY_CLOUD_NAME`   | ✅ Yes   | Cloudinary cloud name             |
| `CLOUDINARY_API_KEY`      | ✅ Yes   | Cloudinary API key                |
| `CLOUDINARY_API_SECRET`   | ✅ Yes   | Cloudinary API secret             |
| `PORT`         | ❌ No   | Default is `8080`                 |

Make sure to set these variables in a `.env` file before running the application.  


Install the dependencies and devDependencies

```sh
$ git clone https://github.com/TechKumarNitish/se-project.git
$ npm install
$ cd server npm install && npm start
$ cd client npm install && npm start
```
Start the server.

```sh
$ cd server 
$ npm install 
```
OR
#### Docker Image for Server

A pre-built Docker image for this project is available on Docker Hub:

[https://hub.docker.com/r/122cs0070/cineverse-backend](https://hub.docker.com/r/122cs0070/cineverse-backend)

To pull and run the Docker container:

```bash
docker pull 122cs0070/cineverse-backend
docker run \
-e NODE_ENV='production' \
--env-file .env \
-p 8080:8080 \
122cs0070/cineverse-backend:latest
```


Start the client.

```sh
$ cd client 
$ npm install 
$ npm start
```

Start from root path
```sh
$ npm run server
$ npm run client
```

### Plugins

CineVerse is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

### Server


| Plugin | README |
| ------ | ------ |
| concurrently | [plugins/concurrently/README.md](https://github.com/kimmobrunfeldt/concurrently/blob/master/README.md) |
| bcryptjs | [plugins/bcryptjs/README.md](https://github.com/dcodeIO/bcrypt.js/blob/master/README.md) |
| express | [plugins/express/README.md](https://github.com/expressjs/express/blob/master/Readme.md) |
| googleapis | [plugins/googleapis/README.md](https://github.com/googleapis/googleapis/blob/master/README.md) |
| jsonwebtoken | [plugins/jsonwebtoken/README.md](https://github.com/auth0/node-jsonwebtoken/blob/master/README.md) |
| mongoose | [plugins/mongoose/README.md](https://github.com/Automattic/mongoose/blob/master/README.md) |
| multer | [plugins/multer/README.md](https://github.com/expressjs/multer/blob/master/README.md)|
| nodemailer | [plugins/nodemailer/README.md](https://github.com/nodemailer/nodemailer/blob/master/README.md) |
| nodemon | [plugins/nodemon/README.md](https://github.com/remy/nodemon/blob/master/README.md) |
| qrcode | [plugins/qrcode/README.md](https://github.com/soldair/node-qrcode/blob/master/README.md) |

### Client

| Plugin | README |
| ------ | ------ |
| fullcalendar | [plugins/fullcalendar/README.md](https://github.com/fullcalendar/fullcalendar/blob/master/README.md) |
| material-ui | [plugins/material-ui/README.md](https://github.com/mui-org/material-ui/blob/master/README.md) |
| moment | [plugins/moment/README.md](https://www.npmjs.com/package/@date-io/moment?activeTab=readme) |
| jspdf | [plugins/jspdf/README.md](https://github.com/MrRio/jsPDF) |
| react | [plugins/react/README.md](https://github.com/facebook/react/blob/master/README.md) |
| react-facebook-login | [plugins/react-facebook-login /README.md](https://github.com/keppelen/react-facebook-login/blob/master/README.md) |
| react-google-login | [plugins/react-google-login/README.md](https://www.npmjs.com/package/react-google-login) |
| react-redux | [plugins/react-redux/README.md](https://github.com/reduxjs/react-redux) |
| react-router-dom | [plugins/react-router/README.md](https://github.com/ReactTraining/react-router/blob/master/README.md) |
| react-slick | [plugins/react-slick/README.md](https://github.com/akiran/react-slick) |
| redux | [plugins/redux/README.md](https://github.com/reduxjs/redux)|

### Todos

 - Add Light Mode / More themes



# Screenshots! 

Movie Page
<img src="https://github.com/TechKumarNitish/image/blob/main/movie.png" />

<details>
  <summary>More Screenshots</summary>
  Booking Page
  <img src="https://github.com/TechKumarNitish/image/blob/main/booking.png" />

  Booking Invitations
  <img src="https://github.com/TechKumarNitish/image/blob/main/invitation.png" />

  Guest Dashboard Page
  <img src="https://github.com/TechKumarNitish/image/blob/main/guest-dashboard.png" />

  My Account Page
  <img src="https://github.com/TechKumarNitish/image/blob/main/my-account.png" />

  Admin Home Page
  <img src="https://github.com/TechKumarNitish/image/blob/main/admin-dashboard.png" />

  Admin Cinema Page
  <img src="https://github.com/TechKumarNitish/image/blob/main/admin-cinemas.png" />

  Admin Movie Page
  <img src="https://github.com/TechKumarNitish/image/blob/main/admin-movies.png" />

  Admin Reservation Page
  <img src="https://github.com/TechKumarNitish/image/blob/main/reservations.png" />

  Admin Reservation Calendar
  <img src="https://github.com/TechKumarNitish/image/blob/main/calendar.png" />
</details>



License
----

MIT

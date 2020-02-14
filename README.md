# MERN Stack: Login

Functioning login using MongoDB, Express, React, and Node.js.

Also uses:
Next.js, Mongoose, Passport.js, Material-UI, bcrypt

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

* [Node.js](https://nodejs.org/en/)

### Installing

A step by step series of examples that tell you how to get a development env running

Install dependencies

```
npm install
```

Start the server
```
npm run dev
```

### Google Registration

Head to http://localhost:3000/login/

### Normal Registration without Google

Head to http://localhost:3000/register/

### Check Login Status
1. Open Web Inspector
2. Open Application tab
3. Copy the value of 'jwt' under 'Cookies' section
4. Go to https://jwt.io/, go to Debugger and paste the 'jwt' value from step 3.

## To Do
1. Better front end template for boilerplate use
2. Explanation of acquiring MongoDB Atlas
3. Explanation of acquiring Google OAuth 2.0 Client ID


## Built With

* [Next.js](https://nextjs.org/) - React framework
* [Express](https://expressjs.com/) - Node.js web framework
* [MongoDB](https://www.mongodb.com/) - Document-based database
* [Passport.js](http://www.passportjs.org/) - Authentication middleware
* [Material-UI](https://material-ui.com/) - Material Design components for React

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Mathew Deal** - *Initial work* - [@saltyshu](https://twitter.com/saltyshu)

See also the list of [contributors](https://github.com/datmeal/mern-login/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* **Jon Preece** - *tutorial* - [Build an authentication system using Node.js, Express, and Passport.js](https://developerhandbook.com/passport.js/node-express-passport-authentication-mini-series/)
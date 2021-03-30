# Melonn Tech Test

Hello! This is the repository of the Technical Assestment for the selection process of Melonn, a company that offers a comprehensive e-commerce fulfillment solution for retailers .

  - [Melonn Website](https://www.melonn.com/)

# About the test

The test consist in build a web application that will help sellers manage their sell orders. Having the following modules

  - A sell orders list
  - A page to see the detailed information of each order
  - A form to create a new sell order and calculate the promise dates in the backend


You should also be able of:
  - See the created sell orders in the orders list, allowed in a volatile memory (e.g Local Storage)
  - Choose between 6 shipping methods provided by Melonn and calculate the promise dates

### Tech

In this project, various tools and technologies were used, the purposes of which will be explained below:

* [React.js](reactjs.org) - A JavaScript library for building the user interfaces
* [Webpack](https://webpack.js.org/) - A static module bundler for the application
* [Expressjs](https://expressjs.com/es/) - Web framework for work with Node.js in the Backend
* [MaterialUI](https://material-ui.com/) - UI boilerplate for the app design system
* [react hook form](https://react-hook-form.com/) - Library to work with forms in an easy, flexible and light way using hooks
* [yup](https://www.npmjs.com/package/yup) - Schema builder for value parsing and validation of the forms


### Installation

You need to have installed [Node.js](https://nodejs.org/) v4+ to run.

Also, you need to have the API key to access to the information provided by the Melonn Team

Clone this repo in your local terminal.

```sh
$ git clone git@github.com:Djkde01/MelonnTechTest.git
```

Go to the root folder of the project and install the dependencies and devDependencies and start the server.

```sh
$ npm install
$ npm run start
```
Now, you need to put the API key in an eviroment variable.

- Create a new file called `.ENV`
- In there, write the variable called `API-KEY` that contains the API key

Finally, open another terminal, go to the Front-end folder and start the web application

```sh
$ cd Front-end
$ npm install
$ npm run start
```

If everything gone well, the app should be running in the port https://localhost/8080


### Development

The application was a huge and very interesting challenge, that allows various and complex solutions

It took almost a week to develop the result that you can see in the `main` branch, and although it is a functional version, it does not meet all the requirements.

However, I want to continue developing the application until it is complete, so I created the `later-work` branch, in which I will upload features that are missing in the version delivered on March 29th
### Todos

 - Write Tests
 - Calculate the promise dates
 - Show the created orders in the orders list
 - Prepare the production build
 - Implement page for Sell order details

License
----

MIT


**Djkde - 2021**

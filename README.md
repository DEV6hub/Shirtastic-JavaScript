# Shirtastic JavaScript Application
Pure javascript implementation of Shirtastic

## Install Node.JS

Node.JS
You can visit `https://nodejs.org/en/` to gather detailed instructions on installing Node.Js.


## To install dependencies

Run `npm install`

## To install Restful Server

The json server will serve rest api's to be used for Shirtastic Javscript Application.By default it will run on
localhost:3000.Go to folder JSON Server at the root level and run below commands in separate terminals each and leave it open and running.

`json-server --watch signup.json`  
`json-server --watch tshirts.json --port 4000`
`json-server --watch contactUs.json --port 5000`

 You can check by typing below urls in your browser to see if the server has spin up.

 `http://localhost:3000/userInfo`
 `http://localhost:4000/tshirts`
 `http://localhost:5000/contactUs`


 ## Run App

 `npm run start`

 ## To view the application on browser, go to below url.

 `http://0.0.0.0:7070/assets/index.html`


References: 
Live reload of all files under assets folder is done using live-server.
For more information on live-server: https://www.npmjs.com/package/light-server

The project structure used for Shirtastic Javascript Application is achieved using https://github.com/volojs/create-template.
For more information on best practises for requirejs javascript project structure: https://requirejs.org/docs/start.html#examples

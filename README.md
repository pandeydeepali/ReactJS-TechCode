# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### steps execution

Step 1: create text input and button with react-bootstrap and handle event on click of button

Step 2: if input value is there call the apis with axios, returning records with array and check the condition of status 200.

Step 3: Data will come from inlined end points url :  https://help-search-api-prod.herokuapp.com   

Step 4: if no data is coming from api, then no data found return.

Step 5: implementation of pagination and display 5 records at a time, when no input is there display alert

other than that as on real time execution created utility function for real time project
please check apiUtil.js, apiConfigUrl.js, service.js


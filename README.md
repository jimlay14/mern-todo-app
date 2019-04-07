This project is a simple TODO app using the MERN stack as outlined in this tutorial: https://codingthesmartway.com/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-1/

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

## In Backend Directory

Use mongo to start a database, using 'todos' as the base table. Then, with nodemon installed, use the following command to start the server listener

### `nodemon server`

## Lessons Learned Writing This:

Don't use 'sudo mongo' or 'sudo mongod' as mongo does not need to be run with admin privileges. It will also make future attempts to run mongo difficult.




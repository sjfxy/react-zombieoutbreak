# Zombie Outbreak (React)

This sample illustrates how to integrate a front-end heavy application built using React with a Go microservice to host it, as well as how to
use the React auto-reloading development modes when developing and to launch the Go server when deploying to the cloud.

To run:

* `npm install -i` - This populates the `node_modules` directory and allows the rest of the application's JavaScript-related functionality to work. Note that you'll need Node and npm installed for this to work.
* `npm run watch` - This launches the application in "watch" mode, which is the name of a script defined in the `package.json` file that is an alias for launching the Webpack development server.

To create a pre-generated `bundle.js` file to prep the application for publication in the cloud:

`npm run build`

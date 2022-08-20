<p align="center">
  <img width="70%"src="assets/images/logo.png">
</p>

# Just Another Text Editor (JATE) 👥 

![License Badge](https://img.shields.io/github/license/jak3ster/My-Text-Editor) ![Top Language](https://img.shields.io/github/languages/top/jak3ster/My-Text-Editor)

  ---
A text editor that runs in the browser, a single-page application that meets the PWA criteria, features data persistence techniques that serve as redundancy in case one of the options is not supported by the browser including a function offline and methods for getting and storing data to an IndexedDB database. Using a package called `idb`, which is a lightweight wrapper around the IndexedDB API, that stores and retries data.

The full-stack application is deployed to Heroku using the [Heroku Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation 🔨

1. Download or clone repository
2. Node.js is required to run the application
3. `npm install` to install the required npm packages

## Usage 📎

* The application is invoked by running `npm start` in the command line  
* Open a browser and navigate to <http://localhost:3000/>
* Shows the homepage to interact with the text editor site.

## Demo and Links 📷

* [Heroku](https://jak3ster-texteditor.herokuapp.com/)
* [Github](https://github.com/jak3ster/My-Text-Editor/)

## Features 🧩

* JavaScript
* [Node.js](https://nodejs.org/en/)
* [Webpack](https://webpack.js.org/)
  * Service Workers
  * Create Manifest
* [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
* npm packages
  * [Express](https://expressjs.com/)
  * if-env
  * concurrently
  * nodemon

## License 📜

  Licensed under the [MIT](LICENSE) license.

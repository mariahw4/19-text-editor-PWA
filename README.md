# 19-text-editor-PWA

## Overview
Your task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Usage](#usage)
- [Author](#author)

## The Challenge

## User Story (given in source data)

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria (given in source data)

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

### Screenshot
Screenshot of text-editor in browser and pop out chrome app
![](./assets/app-screenshot.png)
![](./assets/browser-screenshot.png)


### Links

- Solution URL: [Github Repo](https://github.com/mariahw4/19-text-editor-PWA)
- Live Deployment: [Heroku](https://mw-text-editor-app.herokuapp.com/)

## My process

### Built with

- React
- JavaScript
- Application must have a generated `manifest.json` using the `WebpackPwaManifest` plug-in
- Nodemon
- package called `idb`, which is a lightweight wrapper around the IndexedDB API

## Usage

To install run `npm init` and then `npm i`.

To start `npm run start` will run the application. 

## Author

- Website - [Mariah Wear - Github Profile](https://github.com/mariahw4)
- LinkedIn - [Profile](https://www.linkedin.com/in/mariah-wear-7b1630255/)
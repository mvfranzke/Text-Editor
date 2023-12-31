# Text-Editor
Progressive Web Applications (PWA)

## Description
This is the 18th assignment or challenge for our bootcamp class. Our assignment this week is to build a text editor that runs in the browser. It's a single-page application that meets the PWA criteria.It also features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also works offline.

## Installation

Install babel plugin
```npm install @babel/plugin-proposal-object-rest-spread```

Run ```npm install``` to ensure all dependencies are up to date

Run ```npm run build```to ensure no unresolved issues

To start the application from the root directory```npm run start```

## Usage

URL of Github repository : https://github.com/mvfranzke/Text-Editor

Heroku Deployed Link: https://text-editor-mvfranzke-e81c02cd9b74.herokuapp.com/

![heroku page](/Assets/heroku%20screenshot.jpg)

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

## Credits

Please see below additional resources:

* https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide
* https://www.youtube.com/watch?v=IZGNcSuwBZs
* https://webpack.js.org/concepts/
* https://www.freecodecamp.org/news/an-intro-to-webpack-what-it-is-and-how-to-use-it-8304ecdc3c60/



## License
N/A


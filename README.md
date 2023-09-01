# pwa-text-editor [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
To build a  single-page text editor that runs in the browser and that meets the PWA criteria(client, server, indexDB, serviceworker webpack, lighthouse)

![PWA](https://img.shields.io/badge/PWA-5BB974.svg?style=for-the-badge)
![Lighthouse](https://img.shields.io/badge/Lighthouse-FFA518.svg?style=for-the-badge&logo=lighthouse&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![Service Worker](https://img.shields.io/badge/Service%20Worker-FF5733.svg?style=for-the-badge)
![IndexedDB](https://img.shields.io/badge/IndexedDB-4A90E2.svg?style=for-the-badge)
![Cache](https://img.shields.io/badge/Cache-FFCA28.svg?style=for-the-badge&logo=google-chrome&logoColor=white)
![Server](https://img.shields.io/badge/Server-6DB33F.svg?style=for-the-badge)
![Client](https://img.shields.io/badge/Client-35495E.svg?style=for-the-badge)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://www.ecma-international.org/ecma-262/)
[![Node.js Badge](https://img.shields.io/badge/Node.js-393?logo=nodedotjs&logoColor=fff&style=flat)](https://nodejs.org/en)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
 
## Description
<br>
This is a CMS-style blog site where developers can publish their blog posts and comment on other developers' posts. The application follows the Model-View-Controller (MVC) paradigm in its architectural structure and uses Handlebars.js as the templating language, Sequelize as the Object-Relational Mapping (ORM) tool, and the express-session npm package for authentication. The app is deployed on Heroku.
<br>


## Table of contents
- [License](#License)
- [Installation](#Installation)
- [Usage](#Usage)
- [Screenshots](#Screenshots)
- [Contribution](#Contribution)
- [Test](#Test) 
- [Questions](#Questions)


## License 
This application is licensed under MIT License
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Installation:
To install application locally, follow these steps:

* Clone the repository to your local machine.
* Run npm install to install the required dependencies.


## Usage
* Run npm start to start the server and launch the application.
* Visit http://localhost:3000 in your web browser to access the PWA-Text-Editor.

## User Story
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
## Criteria
```
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
<br>


## Screenshots
* manifest
  
![manifest](https://github.com/soniasebastian/pwa-text-editor/assets/130253087/d3f31fdc-6b73-4f46-a871-9d0eafe56938)

* service worker
  
![service worker](https://github.com/soniasebastian/pwa-text-editor/assets/130253087/cc0d114d-1e33-4218-9fd1-f1309c2b40e1)

* storage
* 
![storage](https://github.com/soniasebastian/pwa-text-editor/assets/130253087/ae704824-029a-4892-aead-44b2f4fb8a49)


## Links
The URL of deployed application in Heroku (https://agile-beyond-46723-89e26365736e.herokuapp.com/)


The URL of the github repository (https://github.com/soniasebastian/pwa-text-editor)


## Contribution:
   Contributions are most welcome such as bug fixes, feature enhancements, documentation improvements and code optimization.

## Tests: 
     No tests are performed in this project as of now.

## Questions :
  View my [GitHub](https://github.com/soniasebastian) profile

  Email me at soniasebastian011@gmail.com for any queries.








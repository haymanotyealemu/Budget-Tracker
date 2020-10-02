# Budget-Tracker (Online/Offline)
![Made by@](https://img.shields.io/badge/License-haymanot-brightgreen.svg)
![License](https://img.shields.io/badge/License-none-blue.svg)

## Description
This is a Progressive Web Application futured by giving the required functionality which is the user can able to add expenses and deposits to their budget with or without a connection.tin this application we utilized the Service Worker and Cache APIs to cache assets and API responses to ensure the application is  working without an internet connection.
## Installation
The application is deployed on Heroku. You can run the application from the following link below.
* https://cryptic-falls-80211.herokuapp.com/
## Usage
* First, clone the repository to your local machine and run `npm install` from your terminal. once the application hooked up on the given port, go to your browser and open it.
* open DevTools and go to the Service Workers pane on the Application panel.and check the Offline checkbox. After checking it, you should see a little yellow warning icon next to the Network panel tab. This icon indicates that you're offline.
* Go back to your application and add either expenses or deposits to the budget form and reload your page...it works! you will get your offline cached file, instead of Chrome's offline dino!
![demo](./public/assets/image/online-offline.gif)
## Credits
* https://codelabs.developers.google.com/codelabs/your-first-pwapp/#4
## Test
none
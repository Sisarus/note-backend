# Note Backend - School project

[LINK TO ACTIVE PAGE](https://note-render-test.onrender.com/)

[LINK TO FRONTEND CODE](https://github.com/Sisarus/note-frontend) - React

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Project Links](#project-links)
* [Features](#features)
* [Project Status](#project-status)

## General info
Notes list backend with note and how important that is. 

## Technologies
Project is created with:
* [Node.js](https://nodejs.org/en)
* [Express](https://expressjs.com/)
     - [Cors](https://expressjs.com/en/resources/middleware/cors.html)

## Setup
To run this project, install it locally using npm:
```
npm install
npm run dev
```

## Project Links

* Opens to [localhost](http://localhost:3001/api/notes)

#### Addresses for data
| Method | Address | Desription |
|------|---------|-------------|
| **GET** | */api/notes*: | Get all notes |
| **POST** | */api/notes*: | Create new note |
| **GET** | */api/notes/:id*: | Get one note by id | 
| **DELETE**| */api/notes/:id*: | Delete one note by id |

## Features
List the ready features here:

 * Find all notes
 * Add note
 * Get note
 * Delete note

## Project Status
Project is: in progress

<!--complete / no longer being worked on. If you are no longer working on it, provide reasons why.

node --inspect index.js


lisää dataa tietokantaan
node mongo.js tietokantasalasana
-->


<!--

npm install eslint --save-dev
npx eslint --init
npm run lint -- --fix


npm test -- tests/note_api.test.js
npm test -- -t 'a specific note is within the returned notes'
npm test -- -t 'notes'


window.localStorage

window.localStorage.setItem('name', 'juha tauriainen')
window.localStorage.getItem('name')
window.localStorage.removeItem('name')

window.localStorage.clear()
-->

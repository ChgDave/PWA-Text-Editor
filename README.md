# 19 Progressive Web Applications (PWA): Text Editor

## Description

This is the week 19 challenge project for the Northwestern coding bootcamp.

The task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

You will deploy this full-stack application to Render using the [Render Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide).

## Table of Contents

- [User Story](#user-story)

- [Installation](#installation)

- [Usage](#usage)

- [License](#license)

- [Github Repo](#github-repo)

- [Video Link](#video-link)

- [Questions](#questions)

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Installation

To insall necessary dependencies, run the following command:

```
npm i
```

## Usage

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
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```

## License

This project is licensed under MIT License

## Github Repo

https://github.com/ChgDave/CMS-Blog

## Deployed link on heroku

https://blogems-a6ce292e1cff.herokuapp.com/

## Questions

If you have any qustions about the repo, open an issue or contact me directly at chgdave@gmail.com. You can also find more of my work at [chgdave](https://github.com/chgdave).

## Review

You are required to submit the following for review:

- The URL of the deployed application

- The URL of the GitHub repository, with a unique name and a README describing the project

---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.

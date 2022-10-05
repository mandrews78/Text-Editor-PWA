# Text Editor- PWA

## Description
This application uses an existing text editor app and adds functionality for it to work as a PWA and to work offline. This application is deployed using Heroku.

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

## Installation
```md
npm install
```
The run the following command:  
```md
npm run start:dev
```

## Usage
Type the following command in terminal.
```md
npm run start
```
## Deployed Application
https://text-editor-prorgwebapp.herokuapp.com/

## Repository
https - https://github.com/mandrews78/Text-Editor-PWA.git    
ssh - git@github.com:mandrews78/Text-Editor-PWA.git


## Screenshots

The following image shows the application's `manifest.json` file:
![ManifestFile](https://user-images.githubusercontent.com/70594281/194132518-d83b1fd2-e97e-420e-99c7-48fcbb4bdab6.png)
The following image shows the application's registered service worker:
![service worker](https://user-images.githubusercontent.com/70594281/194132531-a87e70f5-fd9d-429e-945b-c9921667e6aa.png)
The following image shows the application's IndexedDB storage:
![shows indexDB storage](https://user-images.githubusercontent.com/70594281/194132542-b38f962f-5371-4a29-9038-5cbf01870763.png)

# AngularUniversalCrud

Step by step practical guide on building an Angular 8|9 Universal CRUD (Create, Read, Update, Delete)operation web application with MongoDB Server-side Rendering (SSR).

## Written Article
[Build Angular 8|9 Universal CRUD App with MongoDB SSR](https://www.positronx.io/build-angular-universal-crud-app-with-mongodb-server-side-rendering/)


## Run Angular Universal Project
* Git clone
* Run `npm install`
* Open terminal and run `mongod` to start MongoDB database
* Open another terminal and run `npm run build:ssr && npm run serve:ssr`

## List of Express APIs
* POST Create Song	    /api/create-song
* GET Get All Songs	    /api/get-songs
* GET Get Single Song	/api/get-song/:id
* PUT Update Song	    /api/update-song/:id
* DELETE Delete Song	/api/delete-song/:id
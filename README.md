# aqpanel_doc

The purpose of this project is to manage the client data and return views.

## Development Setup

### Prerequisites


- Install [Node.js] which includes [Node Package Manager][npm]
- Install [MongoDB]


### Install Modules

```console
npm install 
```

### Environmental Variables

For reference, `.env.sample` is added to the project. Rename `.env.sample` to `.env`.

```shell
# .env
MONGODB_URL=
MONGODB_SECRET=
PORT=
SECRET=
````

| Variable       | Details                        | Required
| -------------- | -------------------------------| ---------
| MONGODB_URL    | Mongodb URL                    |   YES       
| MONGODB_SECRET | Mongodb Secret                 |   YES
| PORT           | Express port                   |   NO
| SECRET         | JWT Secret                     |   YES             


## Running Application 

```javascript
node server.js 
````

or 

```javascript
npm start
````

## Application Structure

- `server.js`&nbsp; &nbsp; &nbsp;- The entry point to our application. This file defines our express server.
- `model/` &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;- This folder contains schema for database.
- `routes/`&nbsp; &nbsp; &nbsp; &nbsp; - This folder contains the route definitions for our API.
- `utility/`&nbsp; &nbsp; &nbsp; - This folder contains the common utility functions.
- `test/`&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;- This folder contains the UNIT TEST for APIs.
- `upload/`&nbsp; &nbsp; &nbsp; &nbsp;- This folder contains the public folder for uploading files.

[node.js]: https://nodejs.org/
[npm]: https://www.npmjs.com/get-npm
[MongoDB]: https://www.mongodb.com/
[Himanshu Bansal]: https://github.com/Skillnter/

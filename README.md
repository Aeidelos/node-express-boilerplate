# node-express-boilerplate

Starter project for creating a MVC express server, using

+ express
+ mongoose
+ babel-cli
+ winston and morgan for logging
+ Async/Await

## Installation

Clone the repository and run `npm install`

```
git clone https://github.com/Aeidelos/node-express-boilerplate.git
npm install
```

## Starting the server

```
npm start
```

The server will run on port 8888. You can change this by editing `config.dev.js` file.

## Run server in production with Docker

```
npm run build
```

After npm building the project, go to project root directory, open shell and run:

```
docker build -t node-express-boilerplate.
```

## Debugging with Webstorm

Set babel-node executable as the node interpreter.
Pass node parameters of --preset=babel-preset-es2015

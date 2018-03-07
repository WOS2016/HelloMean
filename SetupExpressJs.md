# (Step 3) Setting up Express.js
- Express.js will communite with MongoDB.
- There are several ways to create Express.js 
  1. Simple : installing body-parser
              $ npm install express body-parser --save
              creating Server.js on root folder.
  2. Separated Server and Client :
                Creating "package.json" to run ">npm install" to create folder "node_modules"
                and create server.js file to access MongoDB.
        reference my C:\VGuanTemp\HelloMEIN
  3. TypeScript : Creating server.ts
        reference (https://github.com/sashank6/mean-angular2-seed)
        how to compile server.ts?

## Start Express.js server
$ node server

Then, visit http://localhost:3000/api

## How to debug express.js
>node --inspect <your_file>.js
>node --inspect server.js

chrome://inspect/#devices




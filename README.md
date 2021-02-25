# sort
TypeScript Pattern (Abstract Class): Sort Array of numbers, String and Linked List <br/>
Configuring the TS Compiler: See, tsconfig.json ("outDir": "./build", "rootDir": "./src") <br/>
Concurrent Compilation and Execution: npm install nodemon concurrently <br/>
Concurrent Compilation and Execution: See, package.json <br/>
"scripts": {
    "start:build": "tsc -w",
    "start:run": "nodemon build/index.js",
    "start": "concurrently npm:start:*"
  }, <br/>
  
  npm start <br/>

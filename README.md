# sort
TypeScript Pattern (Abstract Class): Sort Array of numbers, String and Linked List <br/>
@ Configuring the TS Compiler: See, tsconfig.json ("outDir": "./build", "rootDir": "./src") <br/>
@ Concurrent Compilation and Execution: npm install nodemon concurrently <br/>
@ Concurrent Compilation and Execution: See, package.json <br/>
"scripts": { <br/>
    "start:build": "tsc -w", <br/>
    "start:run": "nodemon build/index.js", <br/>
    "start": "concurrently npm:start:*" <br/>
  }, <br/>
  
 @ npm start <br/>

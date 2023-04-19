Prerequisites

Please make sure that Node.js (version >= 12, except for v13) is installed on your operating system.


Setup

`$ npm i -g @nestjs/cli` </br>
`$ nest new project-name`

Running the application

Step into the project-name directory using `cd project-name` 

`$ npm run start`

This command starts the app with the HTTP server listening on the port defined in the src/main.ts file. Once the application is running, open your browser and navigate to http://localhost:3000/. You should see the Hello World! message.

To watch for changes in your files, you can run the following command to start the application:

`$ npm run start:dev`
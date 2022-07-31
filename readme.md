****************************** LESSON 1 ******************************
https://www.youtube.com/watch?v=Hl7diL7SFw8&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL

React, NodeJs, Express, MySql

MySql Database setup
  Install MySql: https://www.mysql.com/downloads/ 
  Install MySqlWorkbench: https://www.mysql.com/products/workbench/
  Create a database: tutorialdb

Server setup
  cd server 
  $ npm install express cors mysql2 nodemon sequelize sequelize-cli
  $ npx sequelize init

  Create /server/models/Posts.js
  Update /server/config/config.json
  Update /server/index.js

****************************** LESSON 2 ******************************
https://www.youtube.com/watch?v=pJx-HGwaL3w&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=2

install Insomnia: https://insomnia.rest/download
  set up CreatePost: POST http://localhost:3001/posts JSON "title":"",	"postText":"", "username":""} 
  set up GetAllPosts: GET http://localhost:3001/posts 

Set up debugger: launch.json


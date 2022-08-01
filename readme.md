****************************** LESSON 1 ******************************
https://www.youtube.com/watch?v=Hl7diL7SFw8&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL

React, NodeJs, Express, MySql

MySql Database setup
  Install MySql: https://www.mysql.com/downloads/ 
  Install MySqlWorkbench: https://www.mysql.com/products/workbench/
  Create a database: tutorialdb

Server setup
  $ cd server 
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

****************************** LESSON 3 ******************************
https://www.youtube.com/watch?v=DO_wR1tx-O0&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=3

$ cd client
$ npx create-react-app .
$ npm install axios

****************************** LESSON 4 ******************************
https://www.youtube.com/watch?v=lxroBmTiOhI&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=4

$ cd client
$ npm install formik react-query react-router-dom yup

install extension: VS Code ES7+ React/Redux/React-Native/JS snippets
  rfce

Break out App page into functional pages and implement routing
  Add Home page
  Add CreatePost page
  Update App page with page Routing
  
****************************** LESSON 5 ******************************
https://www.youtube.com/watch?v=7dfd92NS7uc&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=5

Add edit link

****************************** LESSON 6 ******************************
https://www.youtube.com/watch?v=pXGIdl2aR4g&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=6

Add comments feature

****************************** LESSON 7 ******************************
https://www.youtube.com/watch?v=2Xr-WddT3Lo&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=7

Adding Comments feature UI

****************************** LESSON 8 ******************************
https://www.youtube.com/watch?v=OGGnjBE5qr0&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=8

Adding User Registration and Login features

$ cd server
$ npm install bcrypt


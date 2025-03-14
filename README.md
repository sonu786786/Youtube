- [App Model Link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj)

# Steps taken to made this App : 
1) node should be installed
2) initialize npm(node-packet-manager) : npm init (in terminal)
3) created .gitignore and .env file in the root directory
4) created public folder inside that temp folder inside that .gitkeep file
5) created src folder in root dir and inside it created (app.js, constants.js, index.js) files
6) updated package.json file like added "type": "module", and "scripts": {
    "dev": "nodemon src/index.js"
  },
7) install nodemon : npm i -D nodemon (in terminal)
8) inside src folder make these folders : controllers, db, middlewares, models, routes, utils
9) install prettier : npm i -D prettier(in terminal)

* What is the use of prettier ?
- Ans) Prettier can be integrated into your editor to format your code automatically when you save a file or commit changes, ensuring that all team members follow the same formatting rules.

10) create 2 files in the root dir for prettier : .prettierrc.json(contains all the formatting and styles), .prettierignore(files that should be ignored by prettier)
11) create a cluster on MongoDB Atlas
12) update .env file with PORT and MONGODB_URI(change password)
13) add DB_NAME in constants.js
14) install the mongoose, express, dotenv packages: npm i mongoose express dotenv(in terminal)
15) we can write MONGODB connection in the index.js page or inside the db folder 
16) in db folder we need to make index.js file and write the code(using async, try and catch) and then we call that page from index.js(of root dir)
17) To check the connection , run : npm run dev

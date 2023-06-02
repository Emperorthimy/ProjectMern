## **Documentation for Project 3**

### Nodejs and nodepm Installation 

`sudo apt update`

`sudo apt upgrade`

`sudo apt-get install -y nodejs`

`node -v`

`npm -v`

![nodejs-Installation-process](./images/nodejs_installation.png)

### Creating todo directory and initializing todo
`mkdir Todo`

`npm init`

![initializing-todo-project](./images/todo_init.png)

### Installing Express.JS and dotenv
`npm install express`

`touch index.js`

`npm install dotenv`

`vim index.js`

`node index.js`

![Express and dotENV-Installation](./images/express%26dotenv_installation.png)
![Index.js](./images/index.js.png)
![Express success](./images/express_succes.png)


### Creating Model for our Application

`mkdir routes`

`cd routes`

`touch api.js`

![Routes directory](./images/routes_dir.png)
![api.js cmd](./images/api.js.png)

### Mongoose Installation and creating Models Directory
`npm install mongoose`

`mkdir models`
`cd models`

`touch todo.js`

`mkdir models && cd models && touch todo.js`

`vim todo.js`

`vim api.js`


![api.js cmd updated](./images/api.js_2.png)

![todo cmd](./images/todo.js.png)




#### MongoDb Connected Successfully
`node index.js`

![MongoDB-Connection-Success](./images/db_success.png)
#### Database Populated with Entries 
![Mongoose-model-directory](./images/db.png)
![Database info](./images/db_info.png)

### Frontend Creation
` npx create-react-app client`

` npm install concurrently --save-dev`

`npm install nodemon --save-dev`

`vi package.json`

`npm run dev`
#### Creating React App
![concurrently and nodemon](./images/concurrently%26nodemon_installation.png)
![creating-React](./images/react_installation.png)



#### React App running on Port 3000
`touch Input.js ListTodo.js Todo.js`

`vi input.js`

![Client folder package](./images/client_package.json.png)
![package](./images/package.jsonn.png)
![ReactAPP-running-on-port-3000](./images/run_server.png)


#### Axios Installation
` npm install axios`

// forgot to screenshot other commands due to errors encountered
#### Todo Running in Browser
`vi ListTodo.js`

`vi Todo.js`

`vi App.js`

`vi App.css`

`vim index.css`

`npm run dev`

![Input and app code](./images/input%26app.png)
![Input code](./images/input.js.png)
![App](./images/App_code.png)
![Todo-running-inBrowser](./images/todo.js.png)
![App success](./images/Todo_app_success.png)
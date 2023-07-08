# ChatCord

> A Realtime Chat Application

A simple realtime chat application made using [React JS](https://reactjs.org/docs/getting-started.html), a JavaScript library to make awesome UI by Facebook, [Node JS](https://nodejs.org/en/docs), [Express JS](https://expressjs.com/en/api.html) and [MongoDB](https://docs.mongodb.com/).

This application uses [React JS](https://reactjs.org/docs/getting-started.html) component oriented UI creation paradigm. All components are written in [JSX](https://reactjs.org/docs/jsx-in-depth.html) and ES6 style and are
combined to get a single build for production purpose using [Webpack 5](https://webpack.js.org/concepts/).

ES6 `module` creation along with `import /export` is used. [Babel](https://babeljs.io/docs/en/babel-preset-react) is used to _transpile_ all [JSX](https://reactjs.org/docs/jsx-in-depth.html) code to vanilla JavaScript code. To install all the dependecies `npm` is used.

Back end is implemented using [Node JS](https://nodejs.org/en/docs), [Express JS](https://expressjs.com/en/api.html) and [MongoDB](https://docs.mongodb.com/). [Atlas](https://www.mongodb.com/cloud/atlas), the _Cloud_ version of [MongoDB](https://docs.mongodb.com/) is used. Real time communication is done using [Socket.io](https://www.npmjs.com/package/socket.io).

This is a _responsive web application_ for viewing in both Mobile and Desktop.

## Features

- Latest features of JavaScript i.e. ES6, ES7, ES8 is used
- [React JS Hooks](https://reactjs.org/docs/hooks-intro.html) are used with Functional components
- ES8 `async/await` is used
- This is Simple Chat Application</li>
- It is a Full Stack Application</li>
- All the user details, group chats and conversations are stored in the [MongoDB Atlas](https://www.mongodb.com/cloud/atlas). 
- Login/Signup as well as Logout feature is added </li>
- Guest User Login added</li>
- Error will be shown if the credentials are not correct</li>
- Real time communication & notification is supported using <a href="https://www.npmjs.com/package/socket.io">Socket.io</a>
 - Realtime One on One chats and group chats </li>
 - Functionality and features like Search for chats, create a group, add or remove partricipants. </li>   
 - typing... animation. </li>
 - Online / Offline status are shown . </li>
 - Read / Unread status of conversation is supported
 - All the conversation are stored in the database i.e. <i>persistant</i>


## Tech Stack

MongoDB, Express, React, Node, Socket.IO, Chakra-UI

## Usage

### Clone the repository:

```
git clone https://github.com/negativebc/chatcord.git
```

### Env Variables

Create a .env file in the root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = <yourMongoDbUri>
JWT_SECRET = <yourSecret>
```

### Install Dependencies (frontend & backend)
### In the Terminal type
```
npm install
cd frontend
npm install
```

### Run

Running frontend (port:3000) & backend (port:5000) 
```
# For running of complete webpage
npm run dev
```

```
# IF Run frontend only
cd frontend
npm start

# IF Run backend only
npm start
```

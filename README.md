# The Guardian


The Guardian API playground.

  - Be able to get a list of articles
  - Be able to search within typing
  - Be able to detail of single article item
  - Be able to sort by oldest or newest

  

### Tech
* React.js - Frontend SPA
* styled-components - Styling component in React
* axios - Browser HTTP request
* Express.js - Node.js server side calling API from The Guardian

### Installation

  
  This repository contains submodules from
  client: https://github.com/joepotibutr/the-guardian-client
  server: https://github.com/joepotibutr/the-guardian-server
  
  You can clone each repo or install all submodules by following the instruction below:

```sh
$ git clone https://github.com/joepotibutr/the-guardian.git

$ cd the-guardian

$ git submodule update --init --recursive

$ cd packages/server

$ npm install

Create .env file in directory folder

Put this line GUARDIAN_API="58bc3342-c5f4-426d-a41d-fe16f9a0dd91” into .env file

$ npm start

Create command line new window and navigate to the-guardian folder

$ cd packages/client

$ npm install

$ npm start
```

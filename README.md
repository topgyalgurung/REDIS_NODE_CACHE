# Redis Caching in Node.js to retrieve data from GitHub api

### Project setup from beginning 

## init 
- npm init -y

## install express, node-fetch to make request to github api, redis 
- npm i express node-fetch redis 

# install nodemon as dev dependency 
- npm i --save-dev nodemon ( or npm i -D nodemon)

## add start script in package.json
- "scripts":{
-     "start": "nodemon index"
- }

## start server
- npm start

### start redis command line 
- redis-cli 

## when we used cache middleware or redis, it takes 5 ms rather than ~100ms
### can check it from chrome developer tools, then go to network and refresh

### To run cloned repo
- npm install
- npm start
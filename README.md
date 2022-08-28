# TechChat



## Run Locally

1-Clone the project

```bash
  git clone https://github.com/nasaomar165/TechChat.git
```
2-Go to the project directory

```bash
  cd TechChat
```
3-Go to the server directory

```bash
  cd server
```
4- Install dependencies in server

```bash
  npm install
```
5- Go to the client folder

```bash
  cd ./client
```
6- Install dependencies in client

```bash
  npm install
```
7- Start the client react project

```bash
  npm run start
```
8- Come back to server

```bash
  cd ./server
```

9- Start Server using node or nodemon

```bash
  node index.js 
```
or
```bash
  nodemon index.js
```

## Environment Variables
To run this project, you will need to add the following environment variables to your server/.env file

`PORT`  start using 5000 

this app using getStream.io to start your free trial signup here :https://getstream.io/chat/

`STREAM_APP_ID` 

`STREAM_API_KEY` 

`STREAM_API_SECRET` 

this app is using twilio to send sms to phone number signup here : https://www.twilio.com/

`TWILIO_ACCOUNT_SID` 

`TWILIO_AUTH_TOKEN` 

`TWILIO_MESSAGING_SERVICE_SID` 

Add all these Variables to `server/.env` file 

# Python Open AI API
Test models served by openAI as APIs and check Python APIs for various functions. Finally, I deploy the my own trained model.


# Quick Start
```
$ git clone https://github.com/dsdanielpark/openai-chatbot
$ cd openai-chatbot
```

## Client Side
```
$ cd client 
$ npm install
$ npm run dev
```

## Server Side
- Before running server side, enter your own OPEN AI API Key to `.env.openai`
```
$ cd server
$ npm install
$ cp ./server/.env.openai .env 
$ npm run server
```
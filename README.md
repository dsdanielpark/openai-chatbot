# Python Open AI API
Test models served by openAI as APIs and check Python APIs for various functions. Finally, I deploy the my own trained model.


# Quick Start
1. Clone Repository
```
$ git clone https://github.com/dsdanielpark/openai-chatbot
$ cd openai-chatbot
```


2. Set Client Side
```
$ npm install --prefix ./client
$ npm run dev
```

3. Set Server Side
- Before running server side, enter your own OPEN AI API Key to `.env.openai`
```
$ npm install --prefix ./server
$ cp ./server/.env.openai .env 
$ npm run server
```

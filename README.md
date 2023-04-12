Development Status :: 2 - Pre-Alpha

# Python Open AI API
Exploring OpenAI APIs: Test out various models from OpenAI using their Python APIs, and learn how they function. Then, deploy a custom-trained model to enhance your project.

- 01/23/2023 Important Notice: Due to the current OpenAI API policy, we are unable to view the inference results.

<br>

# Quick Start

```cmd
$ git clone https://github.com/dsdanielpark/openai-chatbot
$ cd openai-chatbot
$ npm install
$ npm run dev
$ cp env.openai .env 
$ npm run server
```

<br>

# Slow Start
1. Clone Repository
    ```
    $ git clone https://github.com/dsdanielpark/openai-chatbot
    $ cd openai-chatbot
    ```

2. Set Client Side
    ```cmd
    $ cd client 
    $ npm install
    $ npm run dev
    ```

3. Set Server Side <br>
    Before running server side, enter your own OPEN AI API Key in `.env.openai` from this [link](https://platform.openai.com/account/api-keys).

    ```cmd
    $ cd server
    $ npm install
    $ cp env.openai .env                           $ copy env.openai .env     (windonws)
    $ npm run server
    ```
node v16.x.x
<br>

# Model 
gpt-3.5-turbo is used in default code. but you can change any model like thks:
1. Check model list in [here](https://github.com/dsdanielpark/openai-chatbot/blob/main/scripts/api_test.ipynb)
2. Change api model name in `./server/server.js`

<br>

# References
[1] https://platform.openai.com/account/api-keys <br>
[2] https://platform.openai.com/docs/api-reference/authentication

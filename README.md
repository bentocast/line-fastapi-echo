# Line FastAPI Echo :robot:

This Line chat-bot will watch all incoming message, and reply to the sender with the same message. This repo is modified from the [Example from Line](https://github.com/line/line-bot-sdk-python/tree/master/examples/fastapi-echo), using [fastapi](https://fastapi.tiangolo.com/)

## Getting started :white_check_mark:

```
$ export LINE_CHANNEL_SECRET=YOUR_LINE_CHANNEL_SECRET
$ export LINE_CHANNEL_ACCESS_TOKEN=YOUR_LINE_CHANNEL_ACCESS_TOKEN

$ pip install -r requirements.txt
```

Run FastAPI sample

```
$ uvicorn main:app --reload
```

## Deploy :package:
This repo is connected and deployed to Heroku
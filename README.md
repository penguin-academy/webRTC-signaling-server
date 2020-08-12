# webRTC Signaling Server

This is a minimalistic signaling server for webRTC using socket.IO.

## Getting Started

Make sure to have node v12 or later install the dependencies:

```bash
npm install
# or
yarn
```

Now, run the development server:

```bash
npm run dev
# or
yarn dev
```

The server is now open on localhost:8000. You can now use the sever to connect with socket-io client and handle the signaling.

## Deploy on heroku

The easiest way to deploy this application is is to use [heroku](https://heroku.com). You can simply deploy this server using this one click deploy:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/penguin-academy/webRTC-signaling-server)

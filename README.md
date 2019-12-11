# signalr-client

This is a client which works with either [a .NET Core SignalR server](https://github.com/dirkpennings/signalr-dotnetcore-server) or a [NodeJS SignalR server](https://github.com/dirkpennings/signalr-ports/tree/master/signalr-node-server)

## Configuration
Configure the `serverUrl` variable in `js/chat.js`

## Prerequisites
- Of course you need to run a server first
- ```npm i -g serve```

## Run
- ```serve -l 4567```
- Visit [http://localhost:4567](http://localhost:4567)
# web-socket
Design a web socket in go

To build the project in local
docker build -t web-socket-example .

To run the web-socket container (server-side)
docker run -it -p 8888:8888 go-websocket-tutorial

To run the client side (using live-server)
npm install -g live-server [if live-server is not installed]
live-server --entry-file=index.html
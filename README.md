# node-echo-server
Test bed for using readhook to hook node-echo-server application.
## Running
```
docker run -d --rm -p 8080:8080 polyverse/node-echo-server
```
## Running interactively
```
docker run -it --rm -p 8080:8080 polyverse/node-echo-server /bin/sh
node echo-server.js
```

Our application will use a PHP frontend and a Node backend.
Most of the code will come through dev branch
First we create docker-compose.yml
```
touch docker-compose.yml
```

docker-compose.yml file
```
version: "3"

services: 
   players:
     build: ./players

```



### Make dir for players which will contain the dockerfile. It will
also contain server.js and package.json files for the application
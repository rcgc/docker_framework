# docker_framework
express js setup using docker

# Installation


```javascript

    // clone the application with git clone

    // then install the npm modules using
     
    npm install


```


# Running the application


```javascript


    node server.js


```


# Building docker image

```bash

    docker build -t <imagename:version> .
    docker build -t nodejs-test-app:latest .

```



# Running docker container


```bash

    // 9005 port is given since the docker file contains 9005 port
    docker run -it -d -p <outside-port-of-your-choice>:9005 <imagename:version>
    docker run -it -d -p 9002:9005 nodejs-test-app:latest

```



# first-docker-app

build an image, create a container, and open it 

1. docker build -t getting-started .

2. docker run -dp 3000:3000 getting-started

3. go to localhost:3000 on a browser 

delete the container 

1. docker ps // gets the id of the container

2. docker stop <the-container-id>

3. docker rm <the-container-id>



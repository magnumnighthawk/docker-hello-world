# docker-hello-world

Docker hello world setup for a flask app, as described on the Docker tuts

The python code connects to Redis and maintains a counter for every hit from client and returns on the page.

Run the following to get the app running in a container.
NOTE: Make sure docker is installed
```
docker build --tag=dockersayshello .
docker run -p 4000:80 dockersayshello
```
Hit `localhost:4000` on your browser to checkout the response

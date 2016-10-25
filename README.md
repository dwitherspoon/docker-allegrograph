# docker-allegrograph
Dockerfile to create Allegrograph 6.2.1 running on CentOS 7.

# Manually Build 
In order to manually build this docker image you will need to do the following:
```
Download source from GitHub and run the following command:

docker build -t dwitherspoon/allegrograph
```

# Create Docker Container
In order to create the docker container from this docker image, you will need to run the following command:
```
docker run -d -p 10035:10035 --name allegrograph dwitherspoon/allegrograph
```

Once the container is up and running you will be able to access AllegroGraph's webview by:
```
http://localhost:10035
user: super
pwd: super
```

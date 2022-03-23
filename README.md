# Kronicle Docker Compose

This repo contains Docker Compose files for running a demo instance of Kronicle.  

In order to use this repo, you need to have [Docker for Desktop](https://www.docker.com/products/docker-desktop) 
installed.  

Steps to use the Docker Compose files:

```
$ git clone https://github.com/kronicle-tech/kronicle-docker-compose.git
$ cd kronicle-docker-compose
$ docker-compose up
```

When the commands above have run successfully, you should then be able to open the http://localhost:3000 page in your 
browser.  

Note: It can take 30 seconds or so for Kronicle's backend service to start up, so if you get an error when first opening
http://localhost:3000, refreshing the page after a few seconds should resolve the error

Kronicle's web service should also be accessible via http://localhost:3000/api/v1/components

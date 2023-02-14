# TidyVerseDockerTemplate

This is a TidyVerse Docker Template.  
It's to specified in `.env` file.  
Also, this directory bind to volumes.  

Base Images:

* <https://hub.docker.com/r/rocker/tidyverse>

## How to use

```sh
cp .env.sample .env
# Specify your environments
vi .env
docker-compose build
docker-compose up -d
docker-compose down
```

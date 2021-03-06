# Samp Sharp with Docker
This template contains [SampSharp](https://sampsharp.net/) template gamemode with configured Dockerfile. With this, you only need docker to build and run whole project.

## Dependencies
You only need [docker](https://docs.docker.com/get-docker/).

## Quickstart
- Build Samp Sharp docker container. 
``` 
$ docker build Gamemode -t sampsharp-server:latest
```
This command will build gamemode and create container with samp server, SampSharp plugin and gamemode inside.

- Run server container.
```
$ docker run -p 7777:7777/udp sampsharp-server:latest
```

And you should get SA-MP server with SampSharp gamemode running on port 7777 :)

## Known bugs

- [Container crashes on Windows system](https://github.com/Mrucznik/sampsharp-docker-project-template/issues/1)

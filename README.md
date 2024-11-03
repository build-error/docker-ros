# docker-ros
this is a template for running ros in docker container


Command list

```docker
docker build -t my_image .
```

```docker
docker run -it --user ros --network=host --ipc=host -v $PWD/source:/my_source_code --env=DISPLAY=host.docker.internal:0 my_image
```
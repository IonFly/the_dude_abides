# The Dude Abides
simple little repo. stop by, the dude abides.

The dude needs some pointers on how to do some Python coding, man. Like, ugh, ugh, ya know?


## Example run python script
```
docker run -it --rm --name my-running-script -v "$PWD":/usr/src/myapp -w /usr/src/myapp python:3 python your-daemon-or-script.py
```

## View all docker containers
```
docker ps -a
```

## View docker images
```
docker images
```

## Remove docker container
```
docker rm <container name or id>
```

## Remove docker image
```
docker rmi <container name or id>
```

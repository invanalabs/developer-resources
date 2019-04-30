# Docker 


Stop all the containers with a container name prefix
```
docker stop $(docker ps | grep tcl-* | awk '{print $1}')

```

# Reference Sources
- https://stackoverflow.com/a/50854122
- https://linuxize.com/post/how-to-remove-docker-images-containers-volumes-and-networks/

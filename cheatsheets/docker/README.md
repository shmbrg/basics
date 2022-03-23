| docker command                                | description                                       |
|-----------------------------------------|------------------------------------------------|
| `docker run (-it) <image_name> (<command>)` | create and run container from image (with startup command; overwrites default command) |
| `docker run -p 8080:8080 <image_id>` | create and run container from image with port forwarding |
| `docker ps (--all)` | show running containers (or all that have ever been run on server) |
| `docker create <image_name>` | create container from image |
| `docker start -a <container_id>` | start container with default start up command |
| `docker system prune` | delete all containers from system (and more) |
| `docker logs <container_id>` | get container logs |
| `docker stop <container_id>` | stop running container (shutting itself down with cleanup) |
| `docker kill <container_id>` | kills running container immediately |
| `docker exec -it <container_id> <command>` | execute some command directly into running container |
| `docker exec -it <container_id> sh` | open up a shell within running container |
| `docker build (-t <docker_id>/<project_name>:latest) .` | build container from local Dockerfile (with tag) |
| `docker commit -c 'CMD ["<command>"]' <container_id>` | build docker image from (modified) running container with startup command |
| `` |  |
| `` |  |
| `` |  |
| `` |  |
| `` |  |
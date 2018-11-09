### Docker Images, Containers & Registries

### Images
- An image is a static representation of the app or service and its configuration and dependencies.
- An image is an instance of a container.  When an image is started, it gives running container of an image.	
- A Docker image is built up from a series of layers, allowing a minimal amount of data to be sent when transferring images over network.	
- Images are stored in a registry such as docker hub	
- Images are created with the “build“ command	
- Local images can be listed by running command – 'docker images'	or 'docker image ls' for newest versions


### Containers
- Container is runtime object or representation of an image.	
- Containers are lightweight & portable encapsulation of  an environment where applications are run	
- Command – “docker ps” only outputs running containers	
- When a docker image is run using command “docker run” it creates a container from that instance.
- Containers can be run in either active or detached mode.
- Filesystem changes made in a container do not affect the image

### Registries
- Images are stored in a registry
- A Docker image is built up from a series of layers
- An image is a static representation of the app or service and its configuration and dependencies

---

![](https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/container-docker-introduction/media/image5.png)

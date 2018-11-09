## Evolution in the infrastructure

---

**Mainframe to PC's**

90's

**Baremetal to Virtualization**

00's

**Datacenter to Cloud**

10's

**Host to Containers (serverless)**

Current

---


With Docker, we have an incluse solution, both for developers and sys operators. 

Containers are the "Fastest growing cloud enabling technology" that is changing the world. 

### The challenge

in the picture below, maintaining multiple technology stacks across multiple environments was a nightmare earlier. On top of this, one has to also worry about migrating to a different technology, upgrades, etc., which not only makes it more complex, but completely nonviable to support without having huge impact of CTO and operations.

![](https://crunchytechbytz.files.wordpress.com/2018/01/whatisthechallenge.jpg)

### The matrix from hell

If you Google "Matrix from Hell," I am sure you will find lot of articles on how Docker solves the matrix from hell quandary.

So what precisely is the matrix from hell? In simple words, it is the challenge of packaging any application, irrespective of language/frameworks/dependencies, so that it can run on any cloud, irrespective of the underlying OS/hardware/infrastructure.

![matrix](https://crunchytechbytz.files.wordpress.com/2018/01/matrixfromhell.jpg)

### Solution: Intermodal Shipping Container

The introduction of Docker helped in the eliminating of this matrix, by isolating the worries of developers and administrators. Developers can focus on bundling applications and dependencies as containers, without agonizing over underlying hardware/infrastructure. Administrators/DevOps team can concentrate on managing containers, without agonizing over the contents of those containers.

![](https://crunchytechbytz.files.wordpress.com/2018/01/sjippingcontainer.jpg)


### Solution: Benefits for Developers & Administrators

![](https://crunchytechbytz.files.wordpress.com/2018/01/benfits.jpg)

### What is Docker?

Docker is an open platform for developing, shipping & running distributed applications, whether on laptops, data center VMs or cloud. Docker provides the ability to package and run an application in a loosely isolated environment called a container. The Docker Platform consists of multiple product/tools, including the Docker Engine, Images, Containers, and Hub, among others.

![](https://crunchytechbytz.files.wordpress.com/2018/01/docker.jpg)

The Docker platform is the only container platform to build, secure and manage the widest array of applications from development to production both on premises and in the cloud.



### Why Docker?
Docker is all about speed.
- Develop  faster
- Build faster
- Test faster
- deploy faster
- update / upgrade faster
- recover faster
- maintenance faster 

It covers all the lifecycle. 

### Docker Architecture

To allow for an application to be self-contained the Docker approach moves up the abstraction of resources from the hardware level to the Operating System level.
To further understand Docker, let us look at its architecture. It uses a client-server model and comprises of the following components:

- Docker daemon: The daemon is responsible for all container related actions and receives commands via the CLI or the REST API.
- Docker Client: A Docker client is how users interact with Docker. The Docker client can reside on the same host as the daemon or a remote host.
- Docker Objects: Objects are used to assemble an application. Apart from networks, volumes, services, and other objects the two main requisite objects are:
- Images: The read-only template used to build containers. Images are used to store and ship applications.
- Containers: Containers are encapsulated environments in which applications are run. A container is defined by the image and configuration options. At a lower level, you have containerd, which is a core container runtime that initiates, and supervises container performance.
- Docker Registries: Registries are locations from where we store and download (or “pull”) images.

![](https://lh6.googleusercontent.com/OLNkuRtYmA-8DwJ1-gSM9HL4Uxu56ae3yX5deu9997DXNtNEFbaAnuwSTlKFbAlmwH8GqJohKNow8gpDbUj_LPqW1sfXBu7CLDFB2cL5jqCuuLiOc89AKdH2yiYkq-37EdnePetq)




![](https://www.cygnismedia.com/images/post-images/docker-deployment-automation/containers-vs-virtual-machines.jpg)

Both VMs and containers can help get the most out of available computer hardware and software resources. Containers are the new kids on the block, but VMs have been, and continue to be, tremendously popular in data centers of all sizes.

If you’re looking for the best solution for running your own services in the cloud, you need to understand these virtualization technologies, how they compare to each other, and what are the best uses for each. Here’s our quick introduction.

## Basic Definitions — VMs and Containers

#### What are VMs?
A virtual machine (VM) is an emulation of a computer system. Put simply, it makes it possible to run what appear to be many separate computers on hardware that is actually one computer.

The operating systems (“OS”) and their applications share hardware resources from a single host server, or from a pool of host servers. Each VM requires its own underlying OS, and the hardware is virtualized. A hypervisor, or a virtual machine monitor, is software, firmware, or hardware that creates and runs VMs. It sits between the hardware and the virtual machine and is necessary to virtualize the server.

Since the advent of affordable virtualization technology and cloud computing services, IT departments large and small have embraced virtual machines (VMs) as a way to lower costs and increase efficiencies.

VMs, however, can take up a lot of system resources. Each VM runs not just a full copy of an operating system, but a virtual copy of all the hardware that the operating system needs to run. This quickly adds up to a lot of RAM and CPU cycles. That’s still economical compared to running separate actual computers, but for some applications it can be overkill.

That led to the development of containers.

##### Benefits of VMs
All OS resources available to apps
Established management tools
Established security tools
Better known security controls
Popular VM Providers
VMware vSphere
VirtualBox
Xen
Hyper-V
KVM


### What are Containers?

With containers, instead of virtualizing the underlying computer like a virtual machine (VM), just the OS is virtualized.

Containers sit on top of a physical server and its host OS — typically Linux or Windows. Each container shares the host OS kernel and, usually, the binaries and libraries, too. Shared components are read-only. Sharing OS resources such as libraries significantly reduces the need to reproduce the operating system code, and means that a server can run multiple workloads with a single operating system installation. Containers are thus exceptionally “light” — they are only megabytes in size and take just seconds to start. In contrast, VMs take minutes to run and are an order of magnitude larger than an equivalent container.

In contrast to VMs, all that a container requires is enough of an operating system, supporting programs and libraries, and system resources to run a specific program. What this means in practice is you can put two to three times as many as applications on a single server with containers than you can with a VM. In addition, with containers you can create a portable, consistent operating environment for development, testing, and deployment.

Types of Containers
Linux Containers (LXC) — The original Linux container technology is Linux Containers, commonly known as LXC. LXC is a Linux operating system level virtualization method for running multiple isolated Linux systems on a single host.

Docker — Docker started as a project to build single-application LXC containers, introducing several changes to LXC that make containers more portable and flexible to use. It later morphed into its own container runtime environment. At a high level, Docker is a Linux utility that can efficiently create, ship, and run containers.

#### Benefits of Containers
Reduced IT management resources
Reduced size of snapshots
Quicker spinning up apps
Reduced & simplified security updates
Less code to transfer, migrate, upload workloads
Popular Container Providers
Linux Containers
LXC
LXD
CGManager
Docker
Windows Server Containers
Uses for VMs vs Uses for Containers
Both containers and VMs have benefits and drawbacks, and the ultimate decision will depend on your specific needs, but there are some general rules of thumb.

* VMs are a better choice for running apps that require all of the operating system’s resources and functionality, when you need to run multiple applications on servers, or have a wide variety of operating systems to manage.
* Containers are a better choice when your biggest priority is maximizing the number of applications running on a minimal number of servers.




![](https://mapr.com/blog/containers-vs-vms-a-5-minute-guide-to-understanding-their-differences/assets/containers-vs-vms-wide.png)

# Docker
Docker is an operating system for containers. 
Similar to how a virtual machine virtualizes (removes the need to directly manage) server hardware, containers virtualize the operating system of a server. 
Docker is installed on each server and provides simple commands you can use to build, start, or stop containers.
![image](https://github.com/user-attachments/assets/76d56f45-9bc8-4180-b23f-a20458995964)  

## VM
In its simplest form, a virtual machine, or VM, is a digitized version of a physical computer. Virtual machines can run programs and operating systems, store data, connect to networks, and do other computing functions. However, a VM uses entirely virtual resources instead of physical components.
A VM lets you run a virtual machine on any hardware. Docker lets you run an application on any operating system. It uses isolated user-space instances known as containers.
Docker is an open platform for developing, shipping, and running applications. 
Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. 
With Docker, you can manage your infrastructure in the same ways you manage your applications.
Kubernetes helps you to build cloud-native microservices-based apps. 
It also supports containerization of existing apps, thereby becoming the foundation of application modernization and letting you develop apps faster.
Containers are an abstraction at the app layer that packages code and dependencies together. 
Multiple containers can run on the same machine and share the OS kernel with other containers, each running as isolated processes in user space. 
Containers take up less space than VMs (container images are typically tens of MBs in size), can handle more applications and require fewer VMs and Operating systems.
## Docker Container
A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. 
A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.
Containers are an abstraction at the app layer that packages code and dependencies together. 
Multiple containers can run on the same machine and share the OS kernel with other containers, each running as isolated processes in user space. 
Containers take up less space than VMs (container images are typically tens of MBs in size), can handle more applications and require fewer VMs and Operating systems.
## The Docker daemon 
The Docker daemon ( dockerd ) listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes. A daemon can also communicate with other daemons to manage Docker services.  
### Commands:   
  build       Build an image from a Dockerfile  
  history     Show the history of an image  
  import      Import the contents from a tarball to create a filesystem image  
  inspect     Display detailed information on one or more images  
  load        Load an image from a tar archive or STDIN  
  ls          List images  
  prune       Remove unused images  
  pull        Download an image from a registry  
  push        Upload an image to a registry  
  rm          Remove one or more images  
  save        Save one or more images to a tar archive (streamed to STDOUT by default)  
  tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE  

Other reference: https://www.youtube.com/watch?v=H8Lyj2D_cWo  
https://youtu.be/C-bX86AgyiA?si=UQKV5zH3SfmUxjpU  
https://youtu.be/gAkwW2tuIqE?si=koVBI2h6yEsZJNxb  
https://youtu.be/rIrNIzy6U_g?si=8mmW0p9rnMqXmlcF  




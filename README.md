# Docker_Tutorial

# What is Docker?

Docker is a set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages called containers.Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels.

# Steps to Setup and Install Docker on Windows

1) Go to https://docs.docker.com/docker-for-windows/install/
2) Click on download and select either Stable oe Edge Version. I have installed the stable version.
3) Double click on the installer once downloaded.
4) Open terminal and run docker version to check the version and to check if it's installed right.

# Steps to install Docker on AWS

1) Select EC2 and then select Amazon Linux 2 AMI. Click Next.
2) Choose the free tier t2.micro option. We will select 1 instance and the rest configurations will be default. Give it a name, ex DockerHost.
3) For the security configuration, for now allow "All Traffic". Review and Launch by selecting an existing key pair or by creating a new pair.
4) type "yum install docker" and type "y"
5) type "service docker start" and  "service docker status" to check the status of the docker.
6) to run a container type "docker run hello-world"

# Docker Ecosystem

![alt text] (C:\Users\Hima\Dropbox\My PC (DESKTOP-6BSIAMS)\Desktop\Capture.png?raw=true "Title")



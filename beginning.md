---
layout: page
title: The Beginning
permalink: /the-beginning/
---

# What is Inception
Inception is a project where we have to build a dockerized infrastructure where each service has to be in a Docker container to learn the concept of microservices and managing them efficiently with Docker Compose.
# Requirements
* A Docker container that contains NGINX with TLSv1.2 or TLSv1.3 only.
* A Docker container that contains WordPress with php-fpm (it must be installed
and configured) only, without nginx.
* A Docker container that contains only MariaDB, without nginx.
* A volume that contains your WordPress database.
* A second volume that contains your WordPress website files.
* A docker-network that establishes the connection between your containers.
* Your containers must restart automatically in case of a crash.  

**Achieving the following requires learning Docker and Docker Compose for managing them efficiently and learning how to configure each service required which we will talk about in the next sections.**
# Requirements Visualization
![Mandatory Architecture](/assets/images/mandatory_architecture.png)

# Next
[Docker](/docker)
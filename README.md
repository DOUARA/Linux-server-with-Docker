# Description
Preparing a baseline installation of a Linux server to host web applications and securing it from a number of attack vectors.
The prepation includes installation and configuration of Nginx and Docker and deployment of several web applications. 


# Software Installed
- OS: Ubuntu 16.04
- Docker 18.06.1-ce
- Docker-compose version 1.22.0
- Nginx 1.10.3


 # Configurations 
 ## Security
 - Blocking the remote access for the root user
 - Configuring the Uncomplicated Firewall (UFW) to only allow incoming connections for limited services. 
 - Forcing Key-pair Authentication
 
 ## Web applicaitions 
- Installed different web applications: Flask, Wordpress, and static websites. 
- Used Docker Compose to deploy the applications, each application is running on a specific port on the server. 
- Used Nginx to point the applications to their domain names. 
- Installed SSL certaficates: [let's encrypt](https://letsencrypt.org/)
- Installed and configured a backup script to backup Docker volumes automatically to google drive. 
 


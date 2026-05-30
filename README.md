# AWS EC2 Nginx Deployment

## Overview
This project demonstrates how to launch an AWS EC2 instance, connect using SSH, install Nginx, and host a simple web page.

## Technologies Used
- AWS EC2
- Ubuntu
- SSH
- Nginx
- Linux Commands

## Steps Performed

1. Launched an Ubuntu EC2 instance.
2. Created and downloaded a PEM key pair.
3. Configured Security Group:
   - SSH (22)
   - HTTP (80)
4. Connected using SSH:
   ssh -i WebServer.pem ubuntu@<public-ip>

5. Installed Nginx:
   sudo apt update
   sudo apt install nginx -y

6. Started Nginx:
   sudo systemctl start nginx
   sudo systemctl enable nginx

7. Hosted a custom HTML page.

## Outcome
Successfully hosted a web page on AWS EC2 and accessed it through the public IP address.

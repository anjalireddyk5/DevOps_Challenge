# DevOps_Challenge
A project to show case DevOps skills to spin up new web server using Ansible


Project:Using a modern configuration management tool of your choice to spin up a webserver Date: 07/19/2017 Author: Geethanjali

Tools Used: Ansible AWS EC2

Step by Step Process to implement the project

Signed into AWS console
Spinned up an Free Tier RHEL EC2 Instance with t2.Micro.
Installed Ansible on it .RHEL Doesn't have Ansible Pakcage. So, used EPEL to download and Install ansible
Written an Ansible Playbooks 1)to spin up EC2 instance with UBUNTU on top of it. 2)Configured Security group Inbound rules to allow connections only from ports 22,80,443 3)Installed APACHE on top it 4)Modified the HTTPD.CONF file to modify the default Index.html file to show the content mentioned in the requirement 4)Configured HTTPS redirect to HTTP by inserting the code into HTTPD.CONF file 5)Refer to screenshot docs attached to depict the same.

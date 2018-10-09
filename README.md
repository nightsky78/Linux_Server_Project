# Linux_Server_Project
Udacity FSND project to configure linux server and host web application


# Steps to complete the project

1. Create the lightsail server instance and basic configuration:
1.1 Public IP adress is: 52.199.137.66
1.2 The standard user is ubuntu, so I create a new custom user and add it as sudoer to work with.
1.3 Configure Firewall to allow only ssh and http access. 
2.4 create user for the grader and add it to the sudoer group.

2. Install the required software
2.1 download apache and WSGI via apt-get
2.2 download python3 and all related tools
2.3 download all required packages for my project
2.3.1 This was very tricky as I use python3 so I need a different WSGI module and have to set up the venv properly. I followed:
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps very closely in order to get this done. If you do not do this properly the app does not find the modules. 



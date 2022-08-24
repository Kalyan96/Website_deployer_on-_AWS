# EVGarage

This Project performs a phased deployment of a website running on NodeJS containers connected to a backend database. 
- The whole application is deployed on AWS Cloud, which is provisioned with the required networking, security, storage and compute resources using Terraform. 
- Ansible, Git and Python (Boto3 and Paramiko) perform the sequential execution of docker containers ensuring proper connection of the NodeJS and Database components.

Tools/Applications used : AWS Cloud, Ansible, Docker, Terraform, GitHub, Python (Boto3 and Paramiko), Bash

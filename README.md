# HOA3.1_Team6
Hands-on Activity 3.1 -  Services Installation.

## Objectives:
  * 1.1 Evaluate different workload services ranging from web services and relational and transnational databases
  * 1.2 Create different common workload services with Ansible as documentation and execution
  * 1.3 Create a database and web server using Ansible as documentation and execution

## Instructions:
  * Create a new repository named as HOA3.1_Team6
  * Clone the repository on the local machine's terminal by issuing the command git clone <repository-link>
  #### Inside the repository directory:
	1.1 Create a inventory file containing the IP addresses of each server.
	1.2 Create an ansible configuration file.
	1.3 Create a playbook that install the following services on Ubuntu and Centos:
		  	dhcpd
		  	bind9
		  	vsftpd
		  	samba
		  	https
		 	mariadb

   	1.4 Run the command ansible-playbook --ask-become-pass config.yml to verify that each roles were installed correctly.
   * Use git push and commit to upload the local repository content to GitHub repository...

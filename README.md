# Ansible Playbook: Deploy Static Website

## Description

This Ansible playbook automates the deployment of a static website to a web server. The playbook sets up the necessary web server (e.g., Apache) and transfers the static website files to the server.

## Requirements

Ansible: The control machine should have Ansible installed.  
Inventory: Create an inventory file (inventory/hosts) to specify the target web server(s).  
SSH Access: Ensure that SSH key-based authentication is set up between the control machine and the target web server(s).

## Deployment Steps:

1. Clone this repository to your local machine:
``` bash
git clone https://github.com/Kartikdudeja/static-website_ansible.git
cd static-website_ansible
```

2. Customization:  
Update the `inventory` file to specify the target web server(s) where you want to deploy the static website.

3. Execute the playbook using the following command:
``` bash
ansible-playbook -i inventory.ini deploy-static-website.yaml
```

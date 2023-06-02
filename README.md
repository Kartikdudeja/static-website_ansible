# Deploy a Static Website with Ansible

Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.

In this Project, We will be Deploying a Static Website using Ansible Playbook.

## Deployment Steps:

1. Ensure that Ansible Host is able to connect to Target hosts via SSH.
    > Note: Update Target host IP's in the 'inventory.ini' file
2. Run the Playbook using the following command
``` bash
ansible-playbook -i inventory.ini host-static-website.yaml
```

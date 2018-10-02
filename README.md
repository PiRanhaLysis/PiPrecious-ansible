# Ansible playbook for the PiRogue

The following steps must be conducted on a computer where you want to install piprecious. 

## How to use the playbook
### Install ansible
To install ansible, please follow the [Ansible documentation guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

### Run the playbook
Simply run the following command: 
```
ansible-playbook --ask-become-pass -i inventory.ini piprecious.yml
```

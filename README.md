# Ansible playbook for the PiPrecious

The following steps must be conducted on a computer where you want to install piprecious. 

## How to use the playbook
### Install ansible
To install ansible, please follow the [Ansible documentation guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

### Configure the variables

All the variables are in the files `vars/main.yml`.

### Run the playbook
Simply run the following command: 
```
ansible-playbook --ask-become-pass -i inventory.ini piprecious.yml
```

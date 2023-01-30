# Paideia Ansible

The intention of this repo is to avoid any errors when installing the different paideia services and make the process in general much easier.

## Requirements
- Ansible
- On the server:
  - Docker
  - Docker compose
  - git

## Installation
- git clone this repo to your local machine
- copy the contents of the inventory-template folder to for example a folder named inventory
- Go through each file in the inventory folder and adjust according to your needs
- use ansible to run the playbooks you want to run on your server, for example:

```
ansible-playbook -i inventory playbooks/paideia-offchain/paideia-offchain.yml
```

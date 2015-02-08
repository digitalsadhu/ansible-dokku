# ansible-dokku

Provision and ubuntu 14.04 machine with a fully operational dokku environment

## Instructions

### Create inventory file

Create a file called `inventory.txt` by copying `inventory-example.txt`. 
Edit values to taste.

### Run dokku installation

```
ansible-playbook --ask-sudo-pass -i inventory.txt main.yml
```

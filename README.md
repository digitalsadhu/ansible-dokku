# ansible-dokku

Provision an ubuntu 14.04 machine with a fully operational dokku environment.
Also tested successfully on ubuntu 15.04.

## Instructions

### Create inventory file

Create a file called `inventory.txt` by copying `inventory-example.txt`.
Edit values to taste.

### Run dokku installation

```
ansible-playbook --ask-sudo-pass -i inventory.txt main.yml
```

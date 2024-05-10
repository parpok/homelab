
# NOT GONNA LIE I'M LAZY WITH ALL OF THAT

# homelab

This repository is for my Homelab. Mostly stuff like config files

## My Homelabs specs

Well now I run Ubuntu Server 24.04. Other computer runs CentOS Stream but its for a gitlab deployment primarly

## Services

### On storage hosts

- SMB

Under Docker I run:

- Syncthing

### On infra

Git with GitLab package because I don't want to mess with docker on such complicated piece of software

## Runing those playbooks

Simply run

```sh
ansible-playbook `playbook` -i Ansible/inventory.ini --ask-vault-pass

# ask vault pass only usable for samba playbook
```

Running it all

```sh
ansible-playbook Ansible/installsoftware.yml Ansible/ufw.yml Ansible/initcontainerfolders.yml Ansible/installsoftware.yml Ansible/passwordlesssudo.yml Ansible/ping.yml  -i Ansible/inventory.ini  -K;
```


# NOT GONNA LIE I'M LAZY WITH ALL OF THAT

# homelab

This repository is for my Homelab. Mostly stuff like config files ~~for services I decided to set up~~

## My Homelabs specs

Well now I run Ubuntu Server 22.04. ~~The only reason why its because this thing is a bit too loud for me so I don't want to run it 24/7.~~

## Services

### On storage hosts

- SMB

Under Docker I run:

- Syncthing

### On infra

In progress

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

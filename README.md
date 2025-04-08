# ansible-security-patching
Linux-servers-patching-by-playbooks


# Ansible Security Patching for CentOS Servers

This playbook automates the application of security updates on CentOS servers using Ansible.

## Features
- Supports CentOS 7 and 8
- Conditional logic for yum and dnf usage
- Optional automatic reboot if kernel is updated

## 🖥️ Here's the command to run it:

ansible-playbook -i inventory security-patch.yml

## file hierarchy

ansible-security-patching/
├── inventory
└── security-patch.yml


## Inventory Format
```ini
[web]
web1 ansible_host=172.20.1.100 ansible_user=root ansible_ssh_pass=Passw0rd
web2 ansible_host=172.20.1.101 ansible_user=root ansible_ssh_pass=Passw0rd

# ansible-security-patching
Linux-servers-patching-by-playbooks


# Ansible Security Patching for CentOS Servers

This playbook automates the application of security updates on CentOS servers using Ansible.

## Features
- Supports CentOS 7 and 8
- Conditional logic for yum and dnf usage
- Optional automatic reboot if kernel is updated

## Inventory Format
```ini
[web]
web1 ansible_host=172.20.1.100 ansible_user=root ansible_ssh_pass=Passw0rd
web2 ansible_host=172.20.1.101 ansible_user=root ansible_ssh_pass=Passw0rd



ansible-security-patching/
├── inventory
└── security-patch.yml

![image](https://github.com/user-attachments/assets/0054f8f4-ec35-420d-b75f-5f1df134496d)


# Ansible Jool

This is an ansible role for install and bootstrap Jool (is an Open Source SIIT and NAT64 for Linux.).

- Jool Pojects: [GitHub](https://jool.mx/en/index.html)


## Installation
[Ansible Galaxy Project Page](https://galaxy.ansible.com/yas_nyan/jool)

```
ansible-galaxy install yas_nyan.ansible_jool
```

## Requirements
- Ansible: `2.7` or newer
- Host OS: 
  - `Ubuntu 16.04` or newer
  - `Debian 8 ` or newer


## Role Variables
```yml
JOOL_VER: 4.1.4
ENABLED_MODE: "jool" # or jool_siit

```

## Exaple Playbook
```yml
---
- hosts: routers
  become: true
  roles:
    - yas_nyan.ansible_jool

```


## LINCENSE
MIT
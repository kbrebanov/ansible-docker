docker
======

[![Ansible Role](https://img.shields.io/ansible/role/3872.svg)](https://galaxy.ansible.com/list#/roles/3872)

Installs Docker.

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name           | Default | Description                  |
|:---------------|:--------|:-----------------------------|
| docker_version | 1.11.0  | Version of Docker to install |

Dependencies
------------

- kbrebanov.apparmor

Example Playbook
----------------

Install docker
```yaml
- hosts: all
  roles:
    - kbrebanov.docker
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov

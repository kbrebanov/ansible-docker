docker
======

[![Ansible Role](https://img.shields.io/ansible/role/3872.svg)](https://galaxy.ansible.com/list#/roles/3872)

Installs Docker.

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default | Description                  |
|----------------|---------|------------------------------|
| docker_version | 1.7.0   | Version of Docker to install |

Dependencies
------------

- kbrebanov.apparmor

Example Playbook
----------------

Install docker
```
- hosts: all
  roles:
    - { role: kbrebanov.docker }
```

Install older version of docker
```
- hosts: all
  roles:
    - { role: kbrebanov.docker, docker_version: 1.3.3 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov

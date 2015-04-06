docker
======

Installs Docker.

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

None

Dependencies
------------

CentOS:
  - kbrebanov.selinux

Ubuntu:
  - kbrebanov.apparmor

Example Playbook
----------------

Install docker
```
- hosts: all
  roles:
    - { role: kbrebanov.docker }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov

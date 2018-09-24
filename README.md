[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

docker
======

[![Build Status](https://travis-ci.org/kbrebanov/ansible-docker.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-docker)

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

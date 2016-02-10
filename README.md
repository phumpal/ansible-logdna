logdna
------

Installs [logdna](https://logdna.com)

Requirements
======

This role requires Ansible 1.9 or higher.

Dependencies
======

There are currently no dependencies required for this role

Example Playbook
========

Install logdna
```
- hosts: all
  sudo: true

  roles:
    - logdna

  vars:
    api_key:
```

License
====

[MIT](LICENSE)

Author Information
=========

Patrick Humpal

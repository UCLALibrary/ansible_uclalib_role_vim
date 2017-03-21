Role Name [![Build Status](https://travis-ci.org/UCLALibrary/uclalib_role_vim.svg?branch=master)](https://travis-ci.org/UCLALibrary/uclalib_role_vim)
=========

Installs the Vim editor

Requirements
------------

Only supports RHEL-family servers at this time.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```
---
    - name: uclalib_vim_app.yml
      sudo: true
      hosts: servers

    roles:
      - { role: uclalib_role_vim }

```

License
-------

BSD 3-Clause

Author Information
------------------

Hardy Pottinger, UCLA Library

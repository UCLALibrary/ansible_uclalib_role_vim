UCLALib Ansible Role: Vim
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
    - name: uclalib_git_app.yml
      sudo: true
      hosts: servers

    roles:
      - { role: uclalib_role_vim }

```

License
-------

BSD


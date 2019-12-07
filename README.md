Role Name
=========

A brief description of the role goes here.

Requirements
------------

None

Role Variables
--------------

```
argbash_force_install: false
argbash_install_version: "2.8.1"
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      vars:
        argbash_force_install: true
        argbash_install_version: "2.8.1"
      roles:
         - ansible-role-argbash

License
-------

BSD

Author Information
------------------

J. Scherrer
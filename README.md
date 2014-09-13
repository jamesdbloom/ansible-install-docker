Ansible Docker Install Role
===========================

Installs Docker on Ubuntu 12.04.

Example use in a playbook.
```
- name: Install Docker
  hosts: docker
  roles:
    - jamesdbloom.docker
```

Role Variables
--------------

The following role variables are defined:

```
# Set to export docker host on 2375
export_docker_host: true
```

Dependencies
------------

None.

License
-------

Apache v2.0

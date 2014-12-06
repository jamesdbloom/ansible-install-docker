Ansible Docker Install Role
===========================

Installs Docker on Ubuntu 14.04 and exposes Docker Host

Install role:
```bash
sudo ansible-galaxy install jamesdbloom.install-docker --force
```

Use role in playbook:
```
- name: install docker
  hosts: docker
  sudo: true
  roles:
    - jamesdbloom.install-docker
```

Role Variables
--------------

The following role variables are defined:

```
# Set to export docker host
export_docker_host: true

# Set to control docker host ip binding
docker_host_ip: 0.0.0.0

# Set to control docker host port binding
docker_host_port: 2375
```

Dependencies
------------

None.

License
-------

Apache v2.0

Maintainers
-------

[James D Bloom](http://blog.jamesdbloom.com)

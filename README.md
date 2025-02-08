cadvisor
========
[![Ansible Lint](https://github.com/oxivanisher/role-cadvisor/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-cadvisor/actions/workflows/ansible-lint.yml)

Enable cadvisor and corresponding redis docker container.

Role Variables
--------------



| Name                 | Comment                              | Default value                    |
|----------------------|--------------------------------------|----------------------------------|
| cadvisor_ip: 0.0.0.0 | The IP cadvisor is mapped to.        | `0.0.0.0` |


None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Debian clients
  hosts: debian
  roles:
    - role: oxivanisher.linux_server.role-cadvisor
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_server](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_server/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_server).

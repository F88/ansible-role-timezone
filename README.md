
ansible-role-timezone
=========

[![Ansible Galaxy](http://img.shields.io/badge/galaxy-Fx88.timezone-blue.svg?style=flat-square)](https://galaxy.ansible.com/list#/roles/3343)
[![Tag](http://img.shields.io/github/tag/F88/ansible-role-timezone.svg?style=flat-square)](https://github.com/F88/ansible-role-timezone/releases/tag/v0.1)

Role Name
--------------

Ansible Role for confguring system clock and localtime.

Role Variables
--------------

- zone
 - Zone name under the /usr/share/zoneinfo/

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: Fx88.timezone, zone: Asia/Tokyo }
```

License
-------

MIT


Role Name
=========

Ansible Role for confguring system clock and localtime.

Role Variables
--------------

- zone
 - Zone name under the /usr/share/zoneinfo/

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: Fx88.timezone, zone: Asia/Tokyo }

License
-------

MIT


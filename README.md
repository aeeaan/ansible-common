correct.horse.common
=========

This role contains some basic common tasks/handlers. This includes some tasks for installing the EPEL and IUS repositories as well as some handlers for systemd and firewalld.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: common }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)

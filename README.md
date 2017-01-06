Debian-Gitolite
===============

Gitolite allows you to setup git hosting on a central server, with fine-grained access control and many more powerful features.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

- cowops.debian-git

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-gitolite }

Tasks
-----
  - Install dependencies
  - Install [gitolite](http://gitolite.com/)

License
-------

BSD

Role Name
=========

opendkim-config 
  - configure opendkim package and sets opendkim dauemon to use keyTable and signigTable
  - configure postfix to use opendkim milter running on port 8891/tcp

neither opendkim not postfix service is restarted after configuration !!!

Requirements
------------

- postfix installed and configured

Role Variables
--------------

- none

Dependencies
------------

- none

Example Playbook
----------------

basic usage

---
- hosts: mailserver
  roles:
    - opendkim-config

License
-------

BSD

Author Information
------------------

MarQ (lan projekt) https://lp.net.pl

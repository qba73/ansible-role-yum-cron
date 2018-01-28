Role Name
=========

Ansible role for installing and configuring yum-cron utilities.

Requirements
------------

n/a

Role Variables
--------------

todo

Dependencies
------------

n/a

Example Playbooks
-----------------

Example of how to use role:

    - hosts: all
      roles:
         - { role: yum-cron, update_cmd: default }


Example of how to use role and disable updates:

    - hosts: all
      roles:
         - { role: yum-cron, service_enabled: False, service_state: stopped }


Author Information
------------------

[Jakub Jarosz](https://twitter.com/qba73)


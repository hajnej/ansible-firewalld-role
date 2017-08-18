ansible-firewalld-role
=========

This role installs, starts and enables firewalld

Requirements
------------

There is no prerequisities for this role

Role Variables
--------------

There is no variables defined.

Dependencies
------------

This role does not have any dependencies

Example Playbook
----------------

To install, start and enable firewalld on any host from RHEL7 family use this example playbook

    - hosts: all
      become: True
      roles:
      - "ansible-firewalld-role"

License
-------

BSD

Author Information
------------------

Jakub Slatinsky, slatinskyj@gmail.com

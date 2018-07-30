rd-ansible-user-setup
=========

This role sets up and/or removes users from a system, it can add public and private keys and control groups and sets up SUDO users as required.

Requirements
------------

This module requires Ansible 2.4

Role Variables
--------------

See defaults for variables and descriptions and tests/test.yml for usage examples.

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: rd-ansible-user-setup }

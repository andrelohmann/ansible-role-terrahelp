terrahelp
=========

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-terrahelp.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-terrahelp)

Use this role to install terrahelp, a program to en/decrypt terraform state files.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    terrahelp_version: v0.6.3

Example Playbook
----------------

    - hosts: terrahelp
      roles:
         - { role: andrelohmann.terrahelp }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann

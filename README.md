ansible-go
=========

Ansible role for installing Go

Currently supported:
x86-64
Linux

Planned:
x86
Windows

Role Variables
--------------

- **`go_version`**:

    stable (default)/latest/<specific>

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      include_role:
        name: ansible-go
      vars:
        go_version: latest

License
-------

BSD

Author Information
------------------

Varun Chopra

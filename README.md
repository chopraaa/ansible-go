ansible-go
=========

Ansible role for installing Go

Currently supported:
x86-64, Linux

Planned:
x86, Windows

Supporting older releases is largely problematic as Google doesn't like to keep
them [as we can see here](https://storage.googleapis.com/golang/).

Example Playbook
----------------

Currently, no additional variables are supported. The role will automatically
detect the target distribution and architecture and install the latest version
of Go

    - hosts: servers
      include_role:
        name: ansible-go

License
-------

BSD

Author Information
------------------

Varun Chopra

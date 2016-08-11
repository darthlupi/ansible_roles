Role Name
=========
This is VERY simple role that configures a EL 7 system as Cobbler server.

Requirements
------------

This role requires a EL 7 system.
I am not currently checking for that, but that should be changed if I ever make this role public.

Role Variables
--------------
There are no variables.

Dependencies
------------
There are no role dependencies.


Example Playbook
----------------

    - hosts: servers
      roles:
        - cobbler
License
-------

BSD

Author Information
------------------
Robert Lupinek
https://github.com/darthlupi/ansible_roles_and_playbooks


Role Name
=========

Postgres

Requirements
------------

Right now this role expects a RHEL / CentOS 7 system.  This can be easily changed if ever released to the public via galaxy.

Role Variables
--------------

pg_version: Used to set which version of postgres to install. Valid values are "94" and "95".

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: postgres, pg_version: "95" }

License
-------

BSD

Author Information
------------------

Robert Lupinek https://github.com/darthlupi/ansible_roles_and_playbooks

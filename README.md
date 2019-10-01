Ansible Role:  SQL Server
=========

Ansible role to install SQL Server on RHEL/CentOS

Requirements
------------

This role requires PHP to be installed.  For playbooks declaring a list of roles ensure that the PHP role is listed above this role.

Role Variables
--------------

None.

Dependencies
------------

This role installs the `php-sqlsrv` extension requiring PHP to be installed first.  The extension requires the Microsoft `msodbc` package which is why this php extension is installed in this role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: jhd3.ansible_role_sqlserver }

License
-------

MIT

Author Information
------------------

Created in 2019 by James Dugger for Cyberitas Technologies, LLC

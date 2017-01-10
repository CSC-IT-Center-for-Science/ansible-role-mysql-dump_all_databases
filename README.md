[![Build Status](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-mysql-dump_all_databases.svg?branch=master)](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-mysql-dump_all_databases)

ansible-role-mysql-dump_all_databases
=========

Install and configure dump-all-databases.sh

Requirements
------------


Role Variables
--------------

set {{ mysql_root_db_pass }} to template in a password into the dump-all-file file

See defaults/main.yml

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-mysql-dump_all_databases }

License
-------

MIT

Author Information
------------------


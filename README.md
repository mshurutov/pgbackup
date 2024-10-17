PGBACKUP
=========

Role for install and configure backup tool for postgres.

Requirements
------------

This role requires python v3 because python v2 is out of live and ansible-core>=2.13.9.
Role dependencies:
  - mshurutov.common

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

[GPLv2+](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

Chrony
======

[![Build Status](https://travis-ci.org/rvalente/ansible-role-chrony.svg?branch=master)](https://travis-ci.org/rvalente/ansible-role-chrony)

Install and Configure Chrony for time-synchronization of hosts.

Requirements
------------

No requirements.

Role Variables
--------------

Default is to use `pool.ntp.org` but you are able to customize your ntp servers easily by changing the `ntp_servers` array.

Dependencies
------------

No dependencies are necessary.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: rvalente.chrony }

License
-------

See `LICENSE`

Author Information
------------------

Ronald Valente

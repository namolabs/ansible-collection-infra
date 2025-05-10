Role Name
=========

Fetch data from project config file(s) and vault files and present all data in one global structure to
the following playbooks.
It is assumed that the global structure is mapped to the data structure needed by the resp. playbooks
before calling them.

Requirements
------------



Role Variables
--------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }


Notes
-----

The data structure for vms.vm.network must match [cloudinit networking config v2](https://cloudinit.readthedocs.io/en/latest/reference/network-config-format-v2.html).

License
-------

Apache 2

Author Information
------------------

Christian von Stebut, 2025
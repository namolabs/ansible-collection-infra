Role Name
=========

Generate a complete cloudinit config merged from

- defaults provided inside role (defaults/main.yml) (-> cloudinit_defaults)
- content of user provided variable cloudinit_data

The user provided data will take precedence.

Role Variables
--------------

mandatory

- cloudinit_data
- ansible_hashed_password
- ansible_ssh_authorized_key

optional

- locale

License
-------

MIT

Author Information
------------------

Christian von Stebut
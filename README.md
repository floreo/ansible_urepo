Role Name
========

This role installs urepo (https://github.com/hulu/urepo) a universal repository for linux binary packages.

Requirements
------------

Nothing specific.

Role Variables
--------------

None yet.

Dependencies
------------

None.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: ansible_urepo, become: true }

License
-------

Beerware

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

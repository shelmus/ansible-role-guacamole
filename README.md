Role Name
=========

This role will install apache guacamole and dependancies with 3 extentions.

Requirements
------------

N/A

Role Variables
--------------

defaults/main.yml has two variables
extentions_urls: defines which extentions to install
guac_version: which version of guacd and guacamole to install

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

MYSQL_DB
=========

This ansible role is to deploy MySQL on Ubuntu 18.04

Requirements
------------

This role requires ansible (indeed), ssh-server and python

Role Variables
--------------

Variables required are:
- db_name: 
- db_user: 
- db_password:

Dependencies
------------

NONE


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - mysql_db 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

Mysql DB 
=========

This roles install the mysql DB, creates user, DB

Requirements
------------

Debian/Ubuntu 

Role Variables
--------------

DB user, password, DB name

Dependencies
------------

Python roles. all python dependecies should be installed which are listed in the python roles in this playbook

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

-
  name: Deploy a web application
  hosts: flask_db_web_servers
  roles:
    - python
    - deploy_db
    - web_server

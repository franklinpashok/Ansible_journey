web_server roles
=========

This roles installs flask dependencies for python and copies the app.py script on the target and starts the application

Requirements
------------

Need to copy the python script app.py from simple webapp from github repository.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

Flask and flask-mysql modules for the python script to execute

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
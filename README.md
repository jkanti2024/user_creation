Role Name
=========

These are a set of roles for user management using Ansible.

Requirements
------------
The role has been tested with Ansible 2.x


Role Variables
--------------
The username and desired userid should be entered in vars/main.yaml

myusers :
    - name: 'testuser1'
      uid: 10001 
    - name: 'testuser2'
      uid: 10002
    - name: 'testuser3'
      uid: 10003



Additional defaults like shell , ssh id name etc can also be mentioned if needed


Dependencies
------------

Example Playbook
----------------
You can run the following to execute this role

---
- hosts: test
  roles:
      - { role: user_creation }

License
-------

GPL v3

Author Information
------------------
Kanti Jadia jkantihub

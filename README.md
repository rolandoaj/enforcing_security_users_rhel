ADD-USERS
=========

This role let you create admin users on RHEL 8-9 versions, you need to modify the parameters on vars, according your users id, name and uid, it generated a dinamic initial password "pass_usersd.id". Additionally enforcing life cycle, length and rules to create passwords.

Requirements
------------

N/A

Role Variables
--------------

The variables that you can edit, is inside var/main.yml, you have to specify your users name, id and uid, aditionally you can specify the group and guid to yours users and finally the rules to create rules and life cicle.

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      gather_facts: yes
      gather_subset: min
      roles:
         - role: roles/add-users

License
-------

BSD

Author Information
------------------

Developed by Rolando Antonio https://www.linkedin.com/in/rolando-ant-j/

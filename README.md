Role Name
=========

This role let you create admin users on linux servers, you need to modify the parameters on vars, according your users id, name and uid, in addition you can type your password in the main task. Moreover you can specify the permitions inside the template folder.

Requirements
------------

N/A

Role Variables
--------------

The variables that you can edit, is inide var, you have to specify your users name, id and uid, aditionally you can specify the group and guid to yours users.

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

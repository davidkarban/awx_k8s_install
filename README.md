Role Name
=========

Configure AWX on K8s

Requirements
------------

A working k8s

Role Variables
--------------

awx_password: <default = Passw0rd!>

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      vars:
        awx_password: SomeThing8lse

      roles:
         - jesperberth.awx_k8s_install

License
-------

BSD

Author Information
------------------

Jesper Berth
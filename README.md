Role Name
=========

Hopla.cloud role for ansible to install a simple LAMP server.

Requirements
------------

Ubuntu 18.04

Role Variables
--------------

user_name: "username"
user_email: "exemple@domain.com"
php_version "x.x"

Dependencies
------------

- hoplacloud.linux_update
- hoplacloud.linux_motd
- hoplacloud.apache-php
- hoplacloud.fail2ban
- hoplacloud.vhostdeploy_apache
- hoplacloud.proftpd
- hoplacloud.postfix
- geerlingguy.mysql


Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.lamp

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)

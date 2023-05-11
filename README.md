Role Name
=========
draxalene.lamp


Draxalene role for ansible to install a simple LAMP server. (by hopla.cloud)

Requirements
------------

Ubuntu 18.04 or +

Role Variables
--------------

user_name: "username"
user_email: "exemple@domain.com"
php_version "x.x"

Dependencies
------------

- draxalene.linux_update
- draxalene.linux_motd
- draxalene.apache-php
- draxalene.fail2ban
- draxalene.proftpd
- draxalene.postfix
- geerlingguy.mysql


Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - draxalene.lamp

License
-------

GPLv3

Author Information
------------------

Alexandre MOREAU by hopla.cloud

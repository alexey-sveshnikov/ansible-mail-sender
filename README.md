Mail Sender
========

Installs mailutils and postfix, configures postfix to listen on local interface only.


Requirements
------------

Tested on Ubuntu 14.04 and Debian 7.6

Role Variables
--------------

None

Dependencies
------------

None for Ubuntu. Debian users should have sudo installed.

Example Playbook
-------------------------

    - hosts: your-awesome-servers
      roles:
         - alexey.mail-sender

License
-------

BSD

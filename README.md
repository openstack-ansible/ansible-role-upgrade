marklee77.logwatch
==================

logwatch role for Ubuntu.

This role requires the mailserver role, which does not work with Ubuntu Precise,
so cannot be tested using travis currently.

Example Playbook
-------------------------

    - hosts: all
      roles:
        - marklee77.mariadb
        - marklee77.tomcat6
        - marklee77.mailserver
        - marklee77.logwatch

License
-------

GPLv2

Author Information
------------------

http://marklee77.github.io/

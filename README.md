FFmpeg Ansible Role
===================

This Ansible role installs FFmpeg on Debian/Ubuntu and CentOS/Redhat
distros.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Simply assign this role to the server you want to install FFmpeg on.

    - hosts: servers
      roles:
         - { role: mmartinello.ffmpeg }

License
-------

BSD

Author Information
------------------

Mattia Martinello
mattia@mattiamartinello.com

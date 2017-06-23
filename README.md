Dehydrated ansible role
=======================

Requirements
------------

Current Debian or Ubuntu system, optionally apache2 installed

Role Variables
--------------

See the defaults/main.yml file for all variables that are being used, overrule the defaults
in your host or group_vars

dehydrated_run_once:    Set this to true to only run and configure dehydrated on a single node, usefull when config and certificates are stored on a shared filesystem.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sigio.dehydrated }

License
-------

BSD / MIT

Author Information
------------------

Mark Janssen // Sig-I/O Automatisering
http://sig-io.nl


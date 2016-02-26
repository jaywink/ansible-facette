ansible-facette
===============

A [Facette](https://facette.io/) role for [Ansible](https://www.ansible.com/).

Installs Facette, using Apache2 to proxy. Installs a provider, [collectd](https://collectd.org).

After using this role, check out [a short guide](https://blog.facette.io/2014/07/31/facette-101/) on how to create your first graphs using the stats collected by *collectd*.

Requirements
------------

Ubuntu 14.04.

Role Variables
--------------

    facette_hostname: stats.example.com

Dependencies
------------

-

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-facette, facette_hostname: stats.example.com }

License
-------

MIT

Author Information
------------------

Jason Robinson - https://jasonrobinson.me - https://iliketoast.net/u/jaywink

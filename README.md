Apache Exporter
=========

An Ansible role to install Prometheus Apache Exporter on Linux servers.

Requirements
------------

None

Role Variables
--------------

- apache_exporter_port: Port for the apache exporter to listen on
- apache_exporter_scrape_url: URL for Apache Status page

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: apache_exporter_role, apache_exporter_port: 9100 }

License
-------

BSD

Author Information
------------------

Ahmed Shibani <sheipani@gmail.com>
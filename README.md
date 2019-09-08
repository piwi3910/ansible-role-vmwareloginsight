Role Name
=========

This role installs the VMware vRealize Log Insight agent on a system. It implies you already have a VMware vRealize Log Insight deployment which is reachable from the Ansible control host as well as from the managed node. The agent will be automatically sourced from the parent appliance. It has been developed with and tested against v4.7 but should work for other 4.x versions of vRealize Log Insight.

Requirements
------------

Ansible ≥ 2.5 is required. For Debian servers, per the documentation for the apt module, python-apt (python 2) or python3-apt (python 3) is required.
Compatibility is per the vRealize Log Insight server OS list, therefore not all OSs are supported.

Role Variables
--------------

This role contains variables in two locations: defaults/main.yml and vars. However, the only user-configurable variables you need to set are in defaults/main.yml.

Dependencies
------------

External VMware vRealize Log Insight appliance installed and online.
Connectivity from the managed machine to the vRLI appliance.

Example Playbook
----------------

    - hosts: all
      roles:
         - piwi3910.vmware_loginsight

License
-------

MIT

Author Information
------------------

Feel free to contact me on GitHub (https://github.com/piwi3910). All feedback is most welcome.
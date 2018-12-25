Role Name
=========

This role installs the VMware vRealize Log Insight agent on a system. It implies you already have a VMware vRealize Log Insight deployment which is reachable from the Ansible control host as well as from the managed node. The agent will be automatically sourced from the parent appliance.

Requirements
------------

Ansible ≥ 2.5 is required

Role Variables
--------------

This role contains variables in two locations: defaults/main.yml and vars. However, the only user-configurable variables you need to set are in defaults/main.yml.

Dependencies
------------

External VMware vRealize Log Insight appliance installed and online.

Example Playbook
----------------

    - hosts: all
      roles:
         - chipzoller.vmware_loginsight

License
-------

MIT

Author Information
------------------

Feel free to contact me on GitHub (https://github.com/chipzoller) or Twitter (@chipzoller). All feedback is most welcome.
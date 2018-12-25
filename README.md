Role Name
=========

This role installs the VMware vRealize Log Insight agent on a system. It implies you already have a VMware vRealize Log Insight deployment which is reachable from the Ansible control host as well as from the managed node. The agent will be automatically sourced from the parent appliance.

Requirements
------------

Ansible >= 2.5 is required

Role Variables
--------------

This role contains variables in two locations: defaults/main.yml and vars. However, the only user-configurable variables you need to set are in defaults/main.yml.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - loginsight

License
-------

MIT

Author Information
------------------

Feel free to contact me on GitHub (https://github.com/chipzoller) or Twitter (@chipzoller). All feedback is most welcome.
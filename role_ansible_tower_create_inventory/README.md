Role Name
=========

- role_ansible_create_configurations

      This role create configurations of inventories, projects, templates, credentials etc

Role Variables
--------------

- category
- payload
- method
- configuration_id

Dependencies
------------

- master json file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role_ansible_update_configurations
	  vars:
	    category: "inventories"
		payload: { "name": "test-inventory", "organization": "1" }
		method: "POST"
		configuration_id: 1

Testing Platform
----------------

- Red Hat Enterprise Linux Server release 7.6 (Maipo)

Author Information
------------------

- Yasin Faizan S MD

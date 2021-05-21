Role Name
=========

- role_ansible_update_configuratins

      This role updates configurations like credentials, custom-credentials, templates and projects.

Role Variables
--------------

- configuration_id
- method
- payload
- category

Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - role_ansible_pre_check
      vars:
	  vars:
	    category: "inventories"
		payload: { "name": "test-inventory", "organization": "1" }
		method: "PATCH"
		configuration_id: 1
        

Testing Platform
----------------

- Red Hat Enterprise Linux Server release 7.6 (Maipo)

Author Information
------------------

- Yasin Faizan S MD

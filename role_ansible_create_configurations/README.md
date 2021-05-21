Role Name
=========

- role_ansible_create_configurations

      This role create configurations like credentials, custom-credentials, templates and projects.

Role Variables
--------------

- category
- payload
- method

Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - role_ansible_create_configurations
      vars:
        category: "inventories"
		payload: { "name": "test-inventory", "organization": "1" }
		method: POST
        

Testing Platform
----------------

- Red Hat Enterprise Linux Server release 7.6 (Maipo)

Author Information
------------------

- Yasin Faizan S MD

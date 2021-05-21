Role Name
=========

- role_ansible_tower_add_hosts

      This role adds hosts to a inventory

Role Variables
--------------
- org
- inventory_name
- host_description
- hosts_variables
- category_name
- hosts

Dependencies
------------

- master json file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role_ansible_tower_add_hosts
	  vars:
        org: 1
        inventory_name: "test-inventory"
        host_description: "windows 2016 server"
        hosts_variables: ""
        category_name: "inventories"
        hosts: ["10.0.0.0","10.0.0.1"]

Testing Platform
----------------

- Red Hat Enterprise Linux Server release 7.6 (Maipo)

Author Information
------------------

- Yasin Faizan S MD

Role Name
=========

- role_ansible_tower_delete_configuration

      This role delete configurations like organization, custom credentials, inventory, credentials, projects, templates and workflows.

Role Variables
--------------

- category
- task_name
- tower_gui_url
- tower_gui_username
- tower_gui_password
- taskid

Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - role_ansible_tower_delete_configuration
      vars:
        tower_gui_url: "http://10.0.0.1"
        tower_gui_username: "admin"
        tower_gui_password: "password"
        category: "credentials"
        task_name: "serverbuild-release-credentials-windows"
        task_id: 171
        

Testing Platform
----------------

- Red Hat Enterprise Linux Server release 7.6 (Maipo)

Author Information
------------------

- Yasin Faizan S MD

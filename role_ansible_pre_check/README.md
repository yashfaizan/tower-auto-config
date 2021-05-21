Role Name
=========

- role_ansible_pre_check

      This role pre checks for configurations like organization,credentials, custom-credentials, teplates,projects and workflows

Role Variables
--------------

- category
- task_name
- tower_gui_url
- tower_gui_username
- tower_gui_password

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
        tower_gui_url: "http://10.0.0.1"
        tower_gui_username: "admin"
        tower_gui_password: "password"
        category: "credentials"
        task_name: "serverbuild-release-credentials-windows"
        

Testing Platform
----------------

- Red Hat Enterprise Linux Server release 7.6 (Maipo)

Author Information
------------------

- Yasin Faizan S MD

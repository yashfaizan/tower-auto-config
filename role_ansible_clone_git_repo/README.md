Role Name
=========

- role_ansible_clone_git_repo

      This role clones a repository to a specified path in localhost

Role Variables
--------------

- git_repo_url
- clone_dest_path
- branch

Dependencies
------------

- NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role_ansible_clone_git_repo
	  vars:
        git_repo_url: "BitBucket.national.core.bbc.co.uk/scm/bbca/tower-auto-config-configuration-files.git"
        clone_dest_path: "/tmp/tower-config"
        branch: "master"

Testing Platform
----------------

- Red Hat Enterprise Linux Server release 7.6 (Maipo)

Author Information
------------------

- Yasin Faizan S MD

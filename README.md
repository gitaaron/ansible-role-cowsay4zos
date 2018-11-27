Role Name
=========

Cowsay (v 3.03) for z/OS

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.
```
install_prefix: /usr/lpp/rocket/cowsay
```
Where cowsay will be installed.

```
path_to_bash_profile: /usr/local/.bash_profile
```
The bash profile shared by each user that will have access to less.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: cowsay4zos }


License
-------

BSD

Author Information
------------------

Aaron Surty (@gitaaron)

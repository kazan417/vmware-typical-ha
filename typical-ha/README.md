create ha vm
=========

creates a high-availible configuration in vmware.

Requirements
------------
access to vmware cluster is requires
pyvmomi >=8.0.3.0.1
vmware-vcenter
vmware-vapi-common-client

vmware.vmware.vms
python3-pyvmomi
sshpass
Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.
You shold set env variable by command export vmpw="yourvmwarehostpasswrd"
also you should change ip of esxi vmware host in tests/inventory
all other variables in vars/main.yml
Dependencies
------------
 ansible galaxy vmware module required

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPL-2.0-or-later

Author Information
------------------
kazan417@mail.ru 

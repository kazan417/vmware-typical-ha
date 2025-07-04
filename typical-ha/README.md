create ha vm
=========

creates a high-availible configuration in vmware.

this role creates 5 virtual machines and configures them according to high availible scenario
2 load balancers,2 webservers, 1 dns server

Requirements
------------
access to esxi vmware is requires
pyvmomi >=8.0.3.0.1
vmware-vcenter
vmware-vapi-common-client

vmware.vmware.vms
python3-pyvmomi
sshpass
Role Variables
--------------

You shold set env variable  vmpw that stores vmware esxi host password by command export vmpw="yourvmwarehostpasswrd"
also you should change ip of esxi vmware host in tests/inventory
all other variables in vars/main.yml
Dependencies
------------
 ansible galaxy vmware module required

 ansible galaxy vmware.vmware.vms module reqired

Example Playbook
----------------


example in parent directory name: typical-ha-playbook.yml
License
-------

GPL-2.0-or-later

Author Information
------------------
kazan417@mail.ru 

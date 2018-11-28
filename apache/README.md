Role Name
=========
You can use this role to install and configure apache easily 

Requirements
------------

No special requiremnet or runnig this
Role Variables
--------------


I have created three playbook
1. installing apapche and other packages - tasks/install.yml
2. enabling the apapche service -  tasks/service.yml
3. configuring apapchevhost from a template - /task/configure.yml

Dependencies
------------

No dependencies

Example Playbook
----------------

run the playbook ansible-playbook -i test/inventory apacheconfig.yml --extra-vars "domain=domainname"
License
-------

BSD

Author Information
------------------

Jobin James.

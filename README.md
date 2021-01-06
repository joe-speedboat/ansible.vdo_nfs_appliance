Role Name
=========

VDO Backup Storage Appliance

Requirements
------------

* Operating System: CentOS8
* OS Disk: min 10GB
* Data Disk: min 50GB
* CPU: min 4   
* Memory: min 4GB   

Install Role
--------------
```
git clone git@github.com:joe-speedboat/ansible.vdo_nfs_appliance.git /etc/ansible/roles/joe-speedboat.ansible_vdo_nfs_appliance
``` 
Later on I will put this as well into ansible galaxy. But at the moment it is a PoC


Role Variables
--------------

Variables are speaking or documented in defaults/main.yml   
One variable is mandatory: vdoPhyDev 


Dependencies
------------

none


Example Playbook
----------------

Are located in test folder of the role


License
-------

GPLv3


Author Information
------------------

Chris Ruettimann<chris@bitbull.ch>


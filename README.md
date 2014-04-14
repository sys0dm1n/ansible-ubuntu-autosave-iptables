Role Name
========

Auto save iptables rules when you reboot your ubuntu server using ansible role to deploy.

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
-------------------------

Clone the repo to your Ansible roles directory.

In your playbook, just add `ubuntu-autosave-iptables` to your roles list. For example:

	- hosts: yourservers
	  sudo: yes
	  roles:
	  	- ansible-ubuntu-autosave-iptables

License
-------

BSD

Author Information
------------------
sys0dm1n
http://terraltech.com

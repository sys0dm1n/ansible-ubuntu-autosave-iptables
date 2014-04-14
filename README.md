Ubuntu Autosave-iptables on Reboot Ansible role
================================

Auto save iptables rules at reboot on ubuntu with ansible

Usage
================================
Clone the repo to your Ansible roles directory.

In your playbook, just add `ubuntu-autosave-iptables` to your roles list. For example:

	- hosts: yourservers
	  sudo: yes
	  roles:
	  	- ubuntu-autosave-iptables

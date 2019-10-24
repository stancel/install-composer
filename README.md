install_composer
=========

Ansible role to install composer to later be used by other roles and tasks for installing and/or upgrading PHP libraries and dependencies.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Copy and edit *defaults/main.yml* to your *vars/main.yml*

```
	- hosts: your_server
	  vars_files:
	    - vars/main.yml
	  roles:
	    - stancel.install_composer
```

or just pass the variables in the playbook

```
	- hosts: your_server 
	  vars:
	  roles:
	    - stancel.install_composer
```

License
-------

GPLv3

Author Information
------------------

[Brad Stancel](https://github.com/stancel) 
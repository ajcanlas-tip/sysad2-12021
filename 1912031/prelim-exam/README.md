# Directory Summary

**Author:** Arman Ian Isaac A. Sapelino

## Prequisites

* Ansible (installed on local virtual machine)
* SSH (installed on both local and remote machine/s)
* Target Machine: Ubuntu 20.04 Server Edition LTS

## Directory Structure
```
prelim-exam
	roles/
		changemotd/
			tasks/
				main.yml
		createuser/
			tasks/
				main.yml
			files/
				config.yml
		python/
			tasks/
				main.yml
		java/
			tasks/
				main.yml
ansible.cfg*
hosts.list*
.gitignore
README.md
```

* ``ansible.cfg```
	Format for the configuration file:
	```
	
	[defaults]
	inventory=./hosts.list
	remote_user = <REMOTE_USER>
	
	[privilege_escalation]
	become=true
	become_method=sudo
	become_user=root
	become_ask_pass=true
	```

* ``hosts.list```
	Format for the inventory file:
	```
	
	[ubuntu]
	<REMOTE HOST IP>
	```

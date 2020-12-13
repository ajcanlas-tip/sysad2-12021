#### A. How to create an Ansible Configuration  

> Check whether your system have ansible installed first (ansible --version).
> If none, you can install by, in my case. _apk add ansible_. 

- To create an Ansible configuration file, use this command _vim ansible.cfg_.  
- Fill-in then the  file with inventory name, remote username, and privileges.  

#### B. How to create an Ansible Inventory
- To create an Ansible inventory;
	[GROUPNAME]
	x.x.x.x <-- host's IP address

#### C. How to create an Ad-hoc Ansible command with setup and shell module.  
- In creating an Ad-hoc Ansible command, follow this format:
	ansible <groupname> -<module_name> -a "<module_options>"


	

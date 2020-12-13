# How to create an Ansible Configurations  
1. Create file named ansible,cgf  
2. Inside file put two groups named defaults and privilege escalation  
3. In defaults put the path of your inventory and username of remote user  
# How to create an Ansible Inventory
1. Create file the will contain the IP address. The user can group the ip address if needed.  
# How to create an Ad-hoc Ansible command with *setup* and *shell* module  
1. for setup use the command ansible [groupname] -m setup [file]  
2. for shell use the command ansible [groupname] -m shell [linux command]  


# Creating Ansible Configuration
1. Make sure you have ansible package, if not, try to install it using apk add ansible
2. Create a file using vim ansible.cfg
3. Insert the file with the basic infos such as remote user, inventory and privilege escalation.
4. Press ESC then :wq to save the file

# Creating Ansible Inventory
1. Create an inventory file using vim inventory
2. Insert the file with ip address of the different hosts
3. Save the file by pressing ESC then :wq

# Creating Ad-hoc Ansible command with setup ans shell module
1. Make sure you have the files needed like the ansible configuration and inventory
2. Check if you can connect to hosts using ansible -m ping all
3. Use ansible all -m shell -a (linux command) for using the shell module.

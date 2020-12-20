# How to create an Ansible Configuration
1. You have to install first the ansible package and the Python3
2. Check first the version of ansible and Python3
3. Create a file using vim ansible.cfg command
4. Insert the file with the basic infos such as remote user, inventory and privilege escalation.
5. Save the file by pressing ESC the :wq or SHIFT + zz

# How to create an Ansible Inventory
1. Create an inventory file using "vim inventory"
2. Insert the file with ip address of the different hosts
3. Save the file by pressing ESC then :wq or SHIFT + zz

# How to create an AD-hoc Ansible command with setup and shell odule
1. Make sure you have the files like ansible.cfg and inventory
2. Check if you can ping the hosts using ansible -m ping all
3. Use ansible all -m shell -a (linux command) for using the shell module (Ex. ansible all -m shell - "whoami")

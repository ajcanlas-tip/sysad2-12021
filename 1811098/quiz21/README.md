#### I. How to create an Ansible Configuration

1. Before creating an ansible configuration, you must check the python version and the ansible version, and the python must be in python 3 to reflect to the ansible version.

2. Create a configuration file inside your current directory and name it as "ansible.cfg" using vim command as the script area will be a text editor only file.

3. Inside the ansible.cfg file, insert the basic information such as inventory, and the remote user from the other PC. 

4. In exiting, press the ESC key then press the colon key, typing the wq! and press the Enter key.



#### II. How to create an Ansible Inventory

1. Inside the directory where the ansible.cfg file exists, create an inventory file using vim command as the script area will be a text editor only file.

2. The inside of the inventory file using also the vim command and insert the IP address of the remote user of the other PC. 

3. In exiting, press the ESC key then press the colon key, typing the wq! and press the Enter key.



#### III. How to create an Ad-hoc Ansible command with setup and shell module

1. Using the command ansible {groupname created in inventory file} -m setup {module or file}, it will do the setup for the hostname/s included in the groupname.

2. Using the command ansible {groupname created in inventory file} -m shell {linux commands}, it will display the output from the other pc to the current pc.



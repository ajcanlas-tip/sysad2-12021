##1. How to create an Ansible Configuration.

- check if the ansible is installed on your terminal using the command "ansible --version".

- then if it is already installed then, make the ansible configuration by typing the command "vi ansible.cfg" then input all the needed configuration inside the file.

##2. How to create an Ansible Inventory.

- inside the directory where you ansible.cfg file located, make an inventory file using "vi inventory" command then input all the needed info such as ip addresses of the other machines.
- after all of that, save the inventory file by pressing escape key and then type ":wq" then enter.

##3. How to create an Ad-hoc ansible command with setup and shell module.

- while using "ansible (group name) -m setup (module or file)" command, it is the way for the hostname to be setup.
- then using "ansible (group name) -m shell -a (linux commands)", it will run bash commands.

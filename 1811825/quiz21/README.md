## 1. How to create an Ansible Configuration.

- before you create the ansible configuration, you need to check if the ansible is installed
on your virtual box using the "ansible --version" command.

-then after checking, make the ansible configuration by typing the command "touch ansible.cfg".
- Using the command vim, input all the needed configurations inside the ansible.cfg

## 2. How to create an Ansible Inventory.
-inside the directory where your ansible.cfg is located, make and inventory file using
the "touch (inventory name)" command.
- using the command vim, input all the needed info that is needed for the inventory file such
as the ip addresses of the other machines you are trying to connect to.
- after all of that, save the inventory file by pressing the escape key and then type the command
":wq!" command.
## 3. How to create an Ad-hoc ansible command with setup and shell module.
- while using "ansible (group name) -m setup (module or file)" command, it is the way for the 
hostname to be setup
- then using "ansible (group name) -m shell -a (linux commands)", it will run bash commands

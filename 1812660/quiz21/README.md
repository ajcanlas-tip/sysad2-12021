# Quiz 2.1: Ansible


## 1. How to create an Ansible Configuration.


- Before creating the Ansible configuration, you must check if ansible is installed using the "ansible --version" command.


- After checking, create the ansible configuration by typing the command "touch ansible.cfg".


- Using vim, input all the necessary configurations inside ansible.cfg


## 2. How to create an Ansible Inventory.


- From the directory where ansible.cfg is located, create an inventory file using "touch (inventory name)".


- Using vim, input all the necessary information needed for inventory such as ip addresses of the other machines you're trying to connect with.


- Save the inventory file by pressing ESC key and then type ":wq!".


## 3. How to create an Ad-hoc Ansible command with setup and shell module.


- Using "ansible (group name) -m setup (module or file)" command is a way to setup for the hostname.


- Using "ansible (group name) -m shell -a (linux commands)" will run bash commands.

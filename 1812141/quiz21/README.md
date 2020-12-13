## 1. How to create an Ansible configuration.

- Before creating the Ansible configuration, you must check if ansible is installed using "ansible --verson" command.

- After cheking, create the ansible configuration by typing the command "touch ansible.cfg".

- Using vim, input all the necessary configuration inside ansible.cfg.

## 2. How to create an ansible inventory.

- From the directory where ansible.cfg is located, create an inventory file using "touch (inventory name)"

- Using vim, input all the necessary informatio needed for inventory such as ip addresses of the othermachines you're trying to connect with.

- Save the inventory file by pressing ESC key and then type ":wq".

## 3. How to create an Ad-hoc Ansible command with setup and shell module.

- Using "ansible (group name) -m setup (module of file)" command is a way to setup for the hostname.

- Using "ansible (group name) -m shell -a (linux commands)" will run bash commands.

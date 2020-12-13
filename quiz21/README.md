## 1. How to create an Ansible Configuration

- Check the Ansible if it is installed using the command "ansible --version" then create an Ansible Configuration.

- After checking the ansible, create the ansible configuration with the commands "vim ansible.cfg"

- Using the vim command, all the input are necessary configuration inside the ansible.cfg

## 2. How to create an Ansible Inventory

- To create an inventory file, you can use the command "vim inventory"

- Using the vim command, all the input are necesarry needed for inventory such as the ip address of the other servers like the CentOS or Ubuntu.

- After inputting the ip address in the inventory file, select the esc then type the ":wq!" command to save the input inside the inventory file.

## 3. How to create an Ad0hoc Ansible command with setup and shell module

- Using the "ansible (group name) -m setup (module or file) command is a way to setup for the hostanme.

- Using the "ansible (group name) -m shell -a (linux commands" will rush the bash commands.

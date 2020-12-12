## 1. How to creat an Ansible Configuration

- Check the Ansible if it is installed using the "ansible --version" command then create an Ansible Configuration.

- After checking the ansbile, create the ansible configuration with the commands "vim ansible.cfg"

- Using vim comamnd, all the input are necessary configuration inside ansible.cfg

## 2. How to create an Ansible Inventory

- To create an inventory file, you can use the commands "vim inventory"

- Using vim command, all the input are necesarry needed for inventory such as ip address of the other servers such as the CentOS or Ubuntu.

- After inputting the ip address on the inventory file, select the esc then type ":wq!" this command to save the input under the inventory file.

## 3. How to create an Ad-hoc Ansible command with setup and shell module

- Using the "ansible (group name) -m setup (module or file)" command is a way to setup for the hostname.

- Using the "ansible (group name) -m shell -a (linux commands)" willrush the bash commands

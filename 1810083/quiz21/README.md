
### How to create an Ansible Configuration
1. Execute the command `ansible --version` to check of you already install ansible in your OS.
2. Execute the command `apk add ansible` to install it.
3. To create a configuration file use this command `vim ansible.cfg`
4. After creating it go inside of it and input all the information you need.
5. Inside the ansible.cfg one of the things that you need is to input or assign the remote user, inventory name and the privilege escalation.

### How to create an Ansible Inventory
1. Execute the command `vim inventory_filename`.
2. Edit the inventory and insert the host and ip of the servers.
3. To save the file click "esc" then type the ":wq!" command.

### How to create an Ad-hoc Ansible command with setup and shell module
1. To setup the module you can use the command `ansible <hostname> -m setup`.
2. In the shell module use the command `ansible -m shell -a` to run a linux command.

## How to Create an Ansible Configuration
1. Using __ansible --version__ command, check if the ansible was installed. If not installed, use __apk add ansible__ command to install the ansible.
2. Using the command __touch ansible.cfg__, create a file for the configuration.
3. __vim ansible.cfg__ command can be used to open and edit the configuration file. 
4. Insert and type the informations needed such as the inventory, remote user and privilege escalation.
5. To save and quit the file, press __esc_ then type __:wq__.
6. __cat ansible.cfg__ command can be used to view the content of the configuration file.


## How to Create an Ansible Inventory
1. To create a file for ansible inventory, __touch__ and __vim__ command then the filename can be used.
2. Insert and type the IP addresses of the remote machines that will be used.
3. To save and quit the file, press __esc__ then type __:wq__.


## How to Create an Ad-hoc Ansible Command with *setup* and *shell* Module
1. Ping module can be used to check the managed node. (__ansible -m ping Client__ command).
2. To setup the module, __ansible <hostname> -m setup__ can be used.
3. To know more about ad-hoc commands, visit [Introduction to Ad-hoc Commands](docs.ansible.com/ansible/2.8/user_guide/intro_adhoc.html)


# How to create an Ansible Configuration
1. Check if your computer has Ansible by typing with the command "Ansible --version"
2. If not use the command "apk ansible to install the ansible.
3. Create a configuration file name 'ansible.cfg" 
4. Insert basic information such as inventory, host verification, default remote user and privilege escalation
5. Save the File

# How to create Ansible inventory
1. Check if your **ansible configuration file** has the basic information needed
2. Create a file name Inventory using vim
3. Insert IP addresses of your hosts
4. Save the file

# How to create an Ad-hoc Ansible command with setup and shell module
1. Check if your ansible has an ansible.cfg file and inventory file
2. Use command "ansible all -m ping" to verify the ip addresses you stored in the inventory and it should be reacheable with the help of ansible.cfg file
> If unreachable check if you cna enter the hosts via ssh you must configure the inventory file
3. Use command 'ansible all -m shell -a "ls"' to see the files of the all the hosts

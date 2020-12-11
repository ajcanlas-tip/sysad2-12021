# How to create an Ansible Configuration
## Steps
1. Check if the system have ansible or simply type `ansible --version`
2. After that, create a configuration using `vim ansible.cfg`
3. Check the spelling if correct, then insert the information if necessary such as *default remote user*, *inventory*, *host verification*, and *privilege escalation*
4. If you finish it correctly, **save the file now**.

# How to create Ansible Inventory
## Steps
1. First, check the ansible file first if it has the basic information you need.
2. Create a file name using vim inventory
3. After that, Input the necessary IP addresses of the hosts you need
4. Double check if there are no errors, then save the file.

# How to create an Ad-hoc Ansible command with setup and shell module
## Steps
1. Check if you have ansible configuration file and inventory
2. After that, use the command ansible all -m ping to verify the hosts
> If error persists such as unreachable, check if you can enter the host via ssh you must configure the inventory file
3. Use command `ansible all -m shell -a`
4. Check the files of the host using `ls` command


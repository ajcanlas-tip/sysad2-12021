-------------------------------------------------------------------
# How to create an Ansible Configuration
1. Check if your computer has Ansible by typing **`ansible --version`**
2. Create a configuration file name **`ansible.cfg`** using vim
3. Insert basic information such as **inventory, host verification, default remote user and privilege escalation**
4. Save the file

-------------------------------------------------------------------
# How to create Ansible inventory
1. Check if your **ansible configuration** has the basic information needed.
2. Create a file name inventory using vim
3. Insert IP addresses of your hosts
4. Save the file

-------------------------------------------------------------------
# How to create an Ad-hoc Ansible command with setup and shell module
1. Check if your ansible has an configuration file and inventory
2. Use the command **`ansible all -m ping`** to verify the hosts for assurance of connectivity
> Note that if it did not ping or it is unreachable, there might be a problem in your inventory and check if you can connect to hosts via ssh
3. Use comman **`ansible all -m shell -a "ls"`** to see the files of all the hosts

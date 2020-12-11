#how to create an Ansible Configuration 
1. Type "ansible --version" to check if the machine has ansible.
2. Create a configuration file name `ansible.cfg` using vim.
3. Insert the basic information such as inventory, host verification and your default remote user, and privilege escalation.
4. Save the vim file.
**
# How to create an Ansible inventory.
1. Check the ansible configuration if it has the basic information needed.
2. Create a file name `inventory` using vim.
3. Insert the IP addresses of the hosts.
4. Save the vim file.
**
# How to Create an Ad-hoc Ansible command with setup and shell module.
1. Check if your ansible has an **configuration file** and **inventory**.
2. Use the command `ansible all -m ping` to ping the host in the inventory.
> Note; If the command return the ping and both of them are unresponsive there might be a problem to the SSH server,configuratio file or inventory.
3. Use the command `"ansible all -m shell -a "uptime"` to see the uptime of all hosts.

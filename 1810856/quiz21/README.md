-----------------------------------------------------------------------------
# Steps to create Ansbile Configuration (ansible.cfg)

1. Check if your computer whether you have Ansible installed via the command *ansible --version*
2. Create a configuration file name **ansible.cfg**
3. Insert basic informations such as host, inventory, and the default remote user and privilege escalation
4. Then save the file.
-----------------------------------------------------------------------------
# Steps to create the ansible inventory file
1. Check the nesessary basic information inside your ansible configuration
2. Create the file named **inventory**
3. Seperate the name of the hosts and add their individual IP Addresses
4. Then save the file.
-----------------------------------------------------------------------------
# Steps to create Ad-hoc ansible command with setup and shell module
1. First is to check whether you have the files needed like the ansible configuration and its inventory
2. Verify whether you are connected with the code *ansible all -m ping*
> if it is conneted it will reply PONG, if not it will conclude to an error
3. To use the shell module and add linux commands, you could use *ansible all -m shell -a "LINUXCOMMAND"*

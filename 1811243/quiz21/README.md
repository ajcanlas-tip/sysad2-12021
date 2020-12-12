## Create an Ansible Configuration.
1. Make sure you have ansible package in your OS.
2. Create a file using the command `vim ansible.cfg`.
3. Go inside the file and populate the file with a basic information.
4. The file should contain the default remote user, inventory, and/or host verification if necessary.
5. Press the **Esc** key then write and quit to save the file.  
  

## Create an Ansible Inventory.
1. Create the inventory file using the command `vim <inventory_filename>`.
2. Populate the inventory file with the IP address of the host in their respective group.
3. Hit the **Esc** key then write and quiz to save the file.


## Create an Ad-hoc Ansible command with *setup* module.
1. Run the ad-hoc command `ansible <group or host_name> -m setup`.
2. Using the setyp module, you will be able to gather facts about a system. 


## Create an Ad-hoc Ansible command with *shell* module.
1. Run the ad-hoc command `ansible <group or host_name> -m shell -a <bash arguments>`.
2. Using the shell module, you will be able to run a shell-specific syntax.

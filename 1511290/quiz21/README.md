## How To Create an Ansible Configuration
1. Make sure you have ansible package in your OS.
2. Create a file using vim and name it as "ansible.cfg" (e.g vim ansible.cfg")
3. Go to the file and populate the file with the basic information 
4. The file should contain the default remote user, inventory and host verification.
5. Press "esc" then use the ":wq" to save the file.

## How To Create an Ansible Inventory
1. Create an Inventory file using vim (e.g vim inventory_filename)
2. edit the inventory file with IP address of the host in their perspective group
3. Hit "esc" then use ":wq" to save the file 

## How To Create Ad-Hoc Ansible command with *setup* module
1. Run the Ad-Hoc command 'ansible <group or host_name> -m setup'.
2. Using the setup module, you will be able to gather information about the system.

## Create and Ad-Hoc ansible command with *shell* module
1. Run the Ad-hoc command 'ansible <group or host_name> -m shell -a <bash arguments>'.
2. Using the shell module, you are now able to run shell-specific commands/syntax

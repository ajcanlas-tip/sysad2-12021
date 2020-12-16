### HOW TO CREATE AN ANSIBLE CONFIGURATION
Step 1: Install ansible using the command apk add ansible.
Step 2: Create a configuration file by using vim ansible.cfg command.
Step 3: After going inside the config file, input all the information needed such as the inventory, remote user, and privilege escalation.
Step 4: Press the esc button then type the :wq command to save and exit the file.
Step 5: You can check the information inputted by using the cat ansible.cfg command.

### HOW TO CREATE AN ANSIBLE INVENTORY
Step 1: Create an ansible inventory file with the same name of the inventory inputted on the ansible.cfg file.
Step 2: Insert the needed informations such as the hosts and ip addresses.
Step 3: Press the esc button then type the :wq command to save and exit the file.

### HOW TO CREATE AN AD-HOC ANSIBLE COMMAND WITH SETUP AND SHELL MODULE
Step 1: Use the command ansible -m shell -a to run the linux command in shell module.


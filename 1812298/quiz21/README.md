#1. How to create an Ansible Configutraion

- first is to install the ansible using the command "apk add ansible", and do the command
"vim ansible.cfg", and you can input all the configuration needed.

#2. How to create an Ansible Inventory

- inside the ansible.cfg the is "inventory = ./(name of inventory)", to make that inventory
use the command "vim (name of the inventory you made inside the ansible.cfg)", input the 
content of your inventory, then save and quit by pressing the esc on your keyboard then :wq!

#3. How to create an Ad-hoc amsible command with setup and shell module

- The ansible.cfg should be done with right name and ip addresses. Then use the shell commands.

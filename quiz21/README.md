#### A. How to create an Ansible Coniguration

Step 1. Install Ansible using the apk add ansible command  


Step 2. Enter the "vim ansible.cfg" command to configure the created ansible file  


Step 3. After entering the command, input the needed information such inventory, remoter user, and privilege escalation  


Step 4. Exit the file by pressing esc then :wq command  


Step 5. Use the cat command to see the information you have inputed  


#### B. How to create an Ansible inventory  

Step 1. Enter vim ansible.cfg command to enter the ansible file  

Step 2. Input the inventory name with the same name as of the file  

#### C. How to create an Ad-hoc Ansible command with setup and shell module  
Step 1. Enter the "command (hostname) -m setup  

Step 2. Enter the command ansible -m shell -a to run a linux command

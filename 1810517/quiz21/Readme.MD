# How to create an Ansible Configuration
1. Install ansible package using the command **apk add ansible**.
2. Create a file using command **vim ansible.cfg**.
3. Inside the file, insert information such as privelage escalation, inventory and remote user.
4. To exit and save the file, press ESC and enter then type :wq.

# How to create an Ansible Inventory
1. Create an inventory file using the command **vim inventory**.
2. Inside the file, insert the IP adress of the hosts.
3. To exit and save the file, press ESC and enter then type :wq.

# Creating Ad-hoc Ansible command with setup and shell module
1.Inspect if the content of the files are correct especially the content of the inventory file.
2. To check if the hosts are conected use command **ansible -m ping all**.
3. In order to use shell module, enter the command **ansible [groupname] -m shell [linux command]**

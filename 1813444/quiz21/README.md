# **These information are the basic steps on how to create an Ansible Configuration, Inventory, and Ad-hoc command**

## How to create an Ansible Configuration (ansible.cfg) 
**1st step:** To be able to create a file configuration, ansible must installed first using the command _apk add ansible_**.
**2nd step:** Create a file using **touch** command or simply use the _vim_** command to directly create, open, and edit the file.
**3rd step:** Here is the syntax **vi ansible.cfg**. 
**3rd step:** Inside the file, insert the important information such as inventory, remote_user and privilege escalation.
**4th step:** To exit on that interface, press **Esc,** then **:wq!** and all changes will be saved. 
**5th step:** To review the content of the cfg file, **cat ansible.cfg** command can be used.

## How to create an Ansible Inventory
**1st step:** Use **vim** command to create and edit the inventory file. 
**2nd step:** Here is the syntax **vi inventory**
**3rd step:** In this file, insert the IP Addresses of the remote machines that you want to automate. 
**4th step:** To exit on that interface, press **Esc,** then **wq!** and all changes will be saved. 

## How to create an Ad-hoc Ansible Command with setup and shell module
**1st step:** Ping the remote host by using the **ansible -m ping [hostname]** command.
**2nd step:** Then use the **[hostname] -m setup [filename] command to setup the hostname.
**3rd step:** To display the content of the previously setup file, use **ansible [hostname] -m shell -a** command.






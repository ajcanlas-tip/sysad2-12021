## 1. How to create an Ansible Configuration.


-First step is by double checking if ansible is installed using the command "ansible --version" command then you can now proceed ansible configuration.


-Then after checking, create the ansible configuration by typing the command "touch ansible.cfg".


-For vim input all the common configurations inside ansible.cfg


## 2. How to create an Ansible Inventory.


-First step is go to directory then you can see ansible.cfg then create a inventory file using 
"touch(inventory name)".


-Second using vim input all the common information needed for inventory such as ip address of 
other machines you want to connect.


-By saving press esc then ctrl+o then shift ":wq".


## 3. How to create an Ad-hoc Aansible command with setop and module.



-Using the command "ansible (group name) -m shell -a (linux commands)"
will run bash commands.

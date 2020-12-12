# Quiz 2.1: Ansible

## 1. <b> How to create an Ansible Configuration </b>
##	- First thing you will do is to check if you have the ansible  ( to check you can do ansible --version
## 	- If you dont have the ansible you can do `apk add ansible`if you are using alpine this depends on what type of linux you are using.
##	- After installing ansible you can create a ansible configuration by doing `vim ansible.cfg`

##	- Inside the ansible.cfg you'll initialize it first by typing `[defaults]`
##	- After initializing it you'll type certain information the inventory, remote user, and privilege escalation.
##	- after configuring the ansible.cfg you can save it by pressing the esc button -> shift + semicolon -> `wq!` -> enter.
##	-  last thing is to check if you successfully made the ansible.cfg by typing cat ansible.cfg.

## 2. <b> How to create an Ansible Inventory </b>
##	- First thing you will do is check the directory of the inventory and its name that you made inside the ansible cfg.
##	- Next is make an inventory file by typing the same name that you have made inside the ansible.cfg `vim <inventory name>`
##	- Next is to initialize the host name by doing like this `[hostname]`.
##	- After intializing the hostname check the ip of that hostname and put it inside of the inventory file.
##	- After that save it using `write and quit (wq!~)` command.

## 3. <b> How to create an Ad-hoc Ansible Command with setup and shell module </b>
##	-  You can create an Ad-hoc command using an specific module. e.g you can type `ansible <hostname> -m shell ( In this case i used the shell module) -a <bash arguments>`.
##	- You can run any specific syntax depending on what module you've used.


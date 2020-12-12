### How to Create an Ansible Configuration 

1. First check if you have already installed the ansible in your os by entering the `ansible --version` and check the python version on you ansible.

2. if there is no ansible installed in your os you may use the command `apk and ansible`

3. Create a configuration file an name it `ansible.cfg` and use the vim command to see the inside of the file.

4. Edit and add some information such as inventory, remote user, and privilege.

5. Double check the information you entered and exit. press the esc:wq! .

### How to create an Ansible Inventory

1. Check the ansible.cfg if you already created it.

2. Create a file using the command `vim inventory`

3. after execute the command you are inside of the inventory file and type the groupnames and ip addresses. 

4. exit using the command esc:wq! .

### How to create an Ad-hoc ansible command with setup and shell module

1. In creating an ansible ad-hoc, you have to use the command `(hostname) -m setup (module or file)`, it will setup for the hostname included in the groupname.


2. Using the Command `ansible (hostname) -m shell -a (linux command)`, it will display the output of the remote server on your current server. 



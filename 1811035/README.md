### I. How to create an Ansible Configuration

1. As you create an ansible configuration, first check the version of your python and the version of ansible

2. Create an configuration file in your directory and name the file "ansible.cfg" and use vim to see text editor only file

3. After you edit the "ansible.cfg" file, insert the basic inventory information.

4. And lastly when you exit on the text editor on "ansible.cfg" press the ESC button next the colon key and then type wq and press enter to exit the text editor.


### II. How to create an Ansible Inventory

1. Creating a ansible inventory is same as creating an ansible configuration with out the ".cfg" when executing the inventory file it also use vim to go to the text editor only file.

2. After you create the inventory file inside the inventory file is where you will put the other IP Addresses of other computer.

3. And lastly exiting the text editor only file is by pressing ESC then colon and type wq then press Enter.

### III. How to create an Ad-hoc Ansible commnad with setup and shell module

1. Command ansible [groupname in inventory file] -m setup [file], it will setup for the hostname included in the groupname

2. Command ansible [groupname in inventory file] -m shell [linux commands], it will display the output of the other computers on your current pc.

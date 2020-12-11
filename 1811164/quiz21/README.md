---
# HOW TO CRETE an Ansible Configuration
1. Check if your current computer has Ansible with the command "Ansible --version"
2. If not use the command apk add ansible to install the ansible
3. Create a .CFG file [Configuration File] Name " ansible.cfg" using the command vim
4. Insert basic configuration information such as inventory, host verification,default remote suer, and privilege escalation
5. Save the file and view it via Cat to view the information


# HOW TO CREATE an Ansible Inventory
1. Check the ansible cfg file if it has an basic information needed such as remote user and so on
2. create a file name Inventory the will be serve as a ansible inventory
3. insert ip addresses hosts in the inventory file
4. Save the file via Esc > [:wq] command
5. To check if it saved , Use CAT command to view the ip addresses information.


# HOW TO CREATE an Ad-hoc Ansible command with setup and shell module
1. Check the ansible if it has a ansible.cfg File and inventory file.
2. Use command "ansible all -m ping" to verify the ip addresses you stored in the inventory and it should be reacheable with the help of ansible.cfg file.
> if it's unreachable theres something wrong in the inventory file or in the cfg file. IF its permission denied it is mostly in the inventory file.
3. Also you can used "ansible all -m shell -a "ls" to see the files of all the hosts in the inventory listed.

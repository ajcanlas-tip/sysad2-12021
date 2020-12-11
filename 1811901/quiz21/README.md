# How to Create an Ansible Configuration

1. First, check if your machine has ansible installed by using the command `ansible --version`.
1. Use the command `apk add ansible`, if ansible is not installed in your machine.
1. Then, create a configuration file using the command `vim ansicle.cfg`.
1. Insert basic information inside the created file such as inventory, host verification and remote user and privilege escalation.
1. Save the configuration file.

# How to Create an Ansible Inventory

1. Create a file for your inventory using `vim < filename >` or `touch < fileame >`.
1. Insert the IP address of your remote machine.
1. Save the file.

# How to Create a Ad-hoc Ansible Command with _setup_ and _shell_ module

1. First, check if your ansible has configuration and inventory file. Use the command `ls`.
1. Then, ping your remote user with the command `ansible all -m ping`.
1. To input linux commands, use the command `ansible all -m shell -a "whoami" -k`.

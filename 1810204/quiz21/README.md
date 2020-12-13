## Creating an Ansible Configuration

1. Check whether ansible is installed in your machine by typing in the syntax **"ansible --version"**.
1. If not, then install ansible by using the syntax **"apk add ansible"**.
1. After installing ansible, create the configuration file by using **"touch ansible.cfg"** or by directly using **"vim ansible.cfg"**.
1. Then populate the configuration file with the **[defaults]** which are the **"inventory"**, **"remote_user"**, **"private_keys"**, and **"privilege_escalation"** if needed.
1. Lastly, write and save the configuration file to save its changes.

## Creating an Ansible Inventory

1. Create the inventory by using the syntax **"vim inventory"**.
1. Populate the inventory file with the ip address/es of your machine/s.
1. Write and save the inventory file to save its changes.

## Creating an Ad-hoc Ansible command with setup and shell module
1. In creating an Ad-hoc Ansible command with the **setup** module just simply enter the syntax **änsible (target ip or group) -m setup --tree /tmp/facts"**.
- Wherein **"-m"** means that we will initialize what module we should use which is the **"setup"** module. Then using **"--tree /tmp/facts"** to check and display facts about the target machine.
1. With the almost the same syntax but using another module which is the **shell** module, simply tupe the syntax **"ansible (target ip or group) -m shell -a uname"**.
- Wherein **"-m"** means that we will initialize the module which is the **"shell"** module. Then using **"-a"** so we can initialize on what shell command are we going to use. In this situation we used **"uname"** to take and print the name of the operating system that we targeted.

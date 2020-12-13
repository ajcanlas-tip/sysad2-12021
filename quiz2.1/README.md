How to create an Ansible Configuration
1.Create a configuration file in vi using vim ansible.cfg.
2.Go inside the ansible.cfg file and input the information needed.
3.Check the information inside it, it should contain information such as inventory, remote user, privilege escalation.
4.Write and quit using wq.

How to create an Ansible Inventory
1.Make a file inventory with the same name from the ansible.cfg.
2.Insert the needed information such as hosts and ip addresses.
3.Write nad quit using wq.

How to create an Ad-hoc Ansible command with setup and shell module
1.In shell module use the command ansible -m shell -a to run a linux command.

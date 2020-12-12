
## How to create an ansible configuration.

1. Use ansible -- version command to check if the ansible was installed. Make sure that the ansible was installed.
2. Create aa file using vim and name it as "ansible.cfg" (e.g vim ansible.cfg).
3. Go to the file and populate the file with the basic information or the information needed.
4. Insert and type the infomation needed such as inventory, remote user and privilege escalation.
5. Press the "esc" then type ":wq" to save the file.
6. To view the file use the command "cat ansible.cfg"

## How to create an ansible inventory

1. To create an inventory file use the command vim (e.g vim inventory_filename).
2. Edit the inventory file and insert the IP address of the host in their perspective place.
3. To save the file click "esc" then type ":wq" command.

## How to create an Ad-Hoc ansible command with "setup" module.

1. Run the Ad-Hoc command 'ansible<group or host_name> -m setup'.
2. Using the setup module, you will be able to gather information about the system.

## How to create an Ad-Hoc ansible command with "shell" module.

1. Run the Ad-Hoc command 'ansible <group or host_name> -m shell -a <bash arguments>'.
2. Using the shell module, you are now able to run shell-specific commands or syntax.

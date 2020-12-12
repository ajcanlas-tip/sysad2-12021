**How to create an Ansible Configuration**
1. To create an Ansible configuration file, first, you must have Vim and Ansible installed.
2. Go to the directory where you want to store your configuration file. It must be a separate directory as it can cause problems if placed together with another configuration file.
3. Issue the command `vim ansible.cfg`. This will create a text editor and this is where you will edit your configuration file.
4. Start populating your file by first adding `[defaults]` at the topmost part then followed by information of your inventory, remote user/s and privilege escalation.
5. Save your configuration.

**How to create an Ansible Inventory**
1. To create an Ansible inventory, first, you must be in the same directory as your configuration file.
2. Issue the command `vim <inventory name>`. You must use the same file name you used for your inventory information in the configuration file.
3. Populate your inventory file by adding the IP addresses of your remote host/s.
4. Save your file.

**How to create an Ad-hoc Ansible command with __setup__ and __shell__ module**
1. To create an Ansible ad-hoc command using __setup__ module, run the command `ansible <pattern>(specify which host/s or group of hosts from your inventory you want this comamnd to run on) -m setup -a <parameter>`.
2. To create an Ansible ad-hoc command using __shell__ module, run the command `ansible <pattern> -m shell <bash shell argument>`.

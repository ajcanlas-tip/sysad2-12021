## Directory Summary

**Name:** Matienzo, John Edward Sam T.

## Requirements

- Ansible - installed in Alpine.
- SSH - installed and configured in both Alpine and Ubuntu machines.

## Goals

- Create a playbook that installs and configures an vsftpd server.

## Directory Structure

```
README.md
ansible.cfg
ftp_playbook_roles.yaml
inventory
roles/
	vsftpd_centos_config/
			defualts/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				main.yml
			templates/
			tests/
				inventory
				test.yml
			vars/
				main.yml
			README.md
	vsftpd_centos_config/
			defaults/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				main.yml
			templates/
			tests/
				inventory
				test.yml
			vars/
				main.yml
			README.md
vsftpd.conf
vsftpd_centos.conf
````

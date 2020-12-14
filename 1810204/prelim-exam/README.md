## Directory Summary

**Name:** Matienzo, John Edward Sam T.

## Requirements

- Ansible - installed in Alpine
- SSH - installed and configured in both Alpine and Ubuntu Servers.

## Goals

1. To install python3 and pip3 and set as default.
1. To install java into machine.
1. To change the message of the day in Ubuntu
1. To create a new user using the variables inside config.yaml.

## Directory Structure

```
.gitignore
README.md
ansible.cfg
config.yaml
id_rsa
inventory
playbook_prelim.yaml
roles/
	1python/
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
	2java/
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
		READNE.md
	3motd/
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
	4create_user/
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
			test.yaml
		vars/
			main.yml
		README.md
```

## Directory Summary

**Name:** Matienzo, John Edward Sam T.

## Requirements

- Ansible - installed in Alpine.
- SSH - installed and configured in both Alpine and Ubuntu machines.

## Goals

- Create a playbook that installs and configures an httpd server.

## Directory Structure

```
README.md
ansible.cfg
files/
	index.html
	matienzo_domain.conf
	matienzo_domain_centos.conf
inventory
playbook_quiz32_roles.yaml
roles/
	centos_configure/
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
	ubuntu_configure/
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
````

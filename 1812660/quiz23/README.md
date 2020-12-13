# Summary

## Requirements

- Ansible installed in Alpine
- SSH installed to both machines

## Directory Structure

```

README.md
ansible.cfg
files/
	index.html
	lucana_domain.conf
id_rsa
inventory
palybook.yaml
roles/
	step1_role/
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
		README.MD
	
	step2_role/
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
	step3_role/
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
	step4_role
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
	step5_role
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


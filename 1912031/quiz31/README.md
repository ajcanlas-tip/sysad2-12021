# Directory Summary

**Author:** Arman Ian Isaac A. Sapelino

## Prequisites

* Ansible (installed on local machine)
* SSH (installed on both local and remote machine/s)
* Target Machine: Ubuntu 20.04 Server Edition LTS and CentOS 8

## Directory Structure

```
quiz31
	files/
		centos-vsftpd.conf
		ubuntu-vsftpd.conf
	roles/
		configcentosvsftpd/
			defaults/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				main.yml
			tests/
				inventory
				tests.yml
			vars/
				main.yml
		configubuntuvsftpd/
			defaults/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				inventory
				tests.yml
			vars/
				main.yml
		installubuntupkg/
			defaults/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				inventory
				tests.yml
			vars/
				main.yml

		installcentospkg/
			defaults/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				inventory
				tests.yml
			vars/
				main.yml

	ansible.cfg
	hosts.list
	playbook.yml
```



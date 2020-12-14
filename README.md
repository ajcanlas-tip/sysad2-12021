## A. how to create an ansible configuration


> check whether your system have ansible installed first (ansible --version)).
> if none, you can install it by, apk add asinble.



- to create an ansible configuration files, use this command "vim asinble.cfg"
- Fill in the file with inventory name, remote username, and privileges.


## B. how to create an ansible inventory

- to create an ansible inventory:

	[<GROUPNAME>]
	x.x.x.x < -- host's IP address



## C. How to create an Ad-hoc ansible command with setup and shell module.

   -In creating an Ad-hoc ansible command, follow this format:
   ansible <groupname> - <module_name> -a "<module_options>"




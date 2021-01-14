HANDS-ON-ACTIVITY 6: INSTALL, CONFIGURE AND MANAGE ENTERPRISE SERVICES VIA ANSIBLE

===== INSTALLATION OF DHCPD, BIND9, VSFTPD, SAMBA, HTTPD, MARIADB IN BOTH UBUNTU AND CENTOS =====

# DIRECTORIES

___rjsenar-tip___
___Sysad2_12021____
___1810083___
___activity6___
* README.md
* ansible.cfg
* playbook.yaml
* inventory

___roles___
* Installation_for_Ubuntu
* Installation_for_Centos

.
├── README.md
├── ansible.cfg
├── inventory
├── playbook.yaml
└── roles
    ├── Installation_for_Centos
    │   ├── README.md
    │   ├── defaults
    │   │   └── main.yml
    │   ├── files
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    └── Installation_for_Ubuntu
        ├── README.md
        ├── defaults
        │   └── main.yml
        ├── files
        ├── handlers
        │   └── main.yml
        ├── meta
        │   └── main.yml
        ├── tasks
        │   └── main.yml
        ├── templates
        ├── tests
        │   ├── inventory
        │   └── test.yml
        └── vars
            └── main.yml

19 directories, 20 files

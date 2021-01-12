.
├── InvSim
├── README.md
├── ansible.cfg
├── centos_files
│   ├── elasticsearch.repo
│   ├── grafana.repo
│   ├── influxdb.repo
│   ├── logstash.conf
│   └── prometheus.repo
├── config.yaml
├── midterms-exam.yml
├── roles
│   ├── centos
│   │   ├── Elk
│   │   │   ├── README.md
│   │   │   ├── defaults
│   │   │   │   └── main.yml
│   │   │   ├── files
│   │   │   ├── handlers
│   │   │   │   └── main.yml
│   │   │   ├── meta
│   │   │   │   └── main.yml
│   │   │   ├── tasks
│   │   │   │   └── main.yml
│   │   │   ├── templates
│   │   │   ├── tests
│   │   │   │   ├── inventory
│   │   │   │   └── test.yml
│   │   │   └── vars
│   │   │       └── main.yml
│   │   ├── GPI
│   │   │   ├── README.md
│   │   │   ├── defaults
│   │   │   │   └── main.yml
│   │   │   ├── files
│   │   │   ├── handlers
│   │   │   │   └── main.yml
│   │   │   ├── meta
│   │   │   │   └── main.yml
│   │   │   ├── tasks
│   │   │   │   └── main.yml
│   │   │   ├── templates
│   │   │   ├── tests
│   │   │   │   ├── inventory
│   │   │   │   └── test.yml
│   │   │   └── vars
│   │   │       └── main.yml
│   │   ├── Lampstack
│   │   │   ├── README.md
│   │   │   ├── defaults
│   │   │   │   └── main.yml
│   │   │   ├── files
│   │   │   ├── handlers
│   │   │   │   └── main.yml
│   │   │   ├── meta
│   │   │   │   └── main.yml
│   │   │   ├── tasks
│   │   │   │   └── main.yml
│   │   │   ├── templates
│   │   │   ├── tests
│   │   │   │   ├── inventory
│   │   │   │   └── test.yml
│   │   │   └── vars
│   │   │       └── main.yml
│   │   └── Nagios
│   │       ├── README.md
│   │       ├── defaults
│   │       │   └── main.yml
│   │       ├── files
│   │       ├── handlers
│   │       │   └── main.yml
│   │       ├── meta
│   │       │   └── main.yml
│   │       ├── tasks
│   │       │   └── main.yml
│   │       ├── templates
│   │       ├── tests
│   │       │   ├── inventory
│   │       │   └── test.yml
│   │       └── vars
│   │           └── main.yml
│   └── ubuntu
│       ├── Elk
│       │   ├── README.md
│       │   ├── defaults
│       │   │   └── main.yml
│       │   ├── files
│       │   ├── handlers
│       │   │   └── main.yml
│       │   ├── meta
│       │   │   └── main.yml
│       │   ├── tasks
│       │   │   └── main.yml
│       │   ├── templates
│       │   ├── tests
│       │   │   ├── inventory
│       │   │   └── test.yml
│       │   └── vars
│       │       └── main.yml
│       ├── GPI
│       │   ├── README.md
│       │   ├── defaults
│       │   │   └── main.yml
│       │   ├── files
│       │   ├── handlers
│       │   │   └── main.yml
│       │   ├── meta
│       │   │   └── main.yml
│       │   ├── tasks
│       │   │   └── main.yml
│       │   ├── templates
│       │   ├── tests
│       │   │   ├── inventory
│       │   │   └── test.yml
│       │   └── vars
│       │       └── main.yml
│       └── Lampstack
│           ├── README.md
│           ├── defaults
│           │   └── main.yml
│           ├── files
│           ├── handlers
│           │   └── main.yml
│           ├── meta
│           │   └── main.yml
│           ├── tasks
│           │   └── main.yml
│           ├── templates
│           ├── tests
│           │   ├── inventory
│           │   └── test.yml
│           └── vars
│               └── main.yml
└── ubuntu_files
    ├── 02-beats-input.conf
    ├── 10-syslog-filter.conf
    ├── 30-elasticsearch-output.conf
    └── filebeat.yml

68 directories, 70 files

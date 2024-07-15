# asterisk-codebase
.
├── ansible
│   ├── playbooks
│   │   ├── apply-calico-network-policies.yml
│   │   ├── deploy-asterisk.yml
│   │   └── deploy-kamailio.yml
│   └── roles
│       ├── asterisk
│       │   └── tasks
│       │       └── main.yml
│       ├── calico
│       │   └── tasks
│       │           └── main.yml
│       └── kamailio
│           └── tasks
│               └── main.yml
├── helm
│   ├── asterisk
│   │   ├── templates
│   │   │   ├── deployment.yaml
│   │   │   └── service.yaml
│   │   ├── Chart.yaml
│   │   └── values.yaml
│   ├── kamailio
│   │   ├── templates
│   │   │   ├── deployment.yaml
│   │   │   └── service.yaml
│   │   ├── Chart.yaml
│   │   └── values.yaml
│   └── values
│       └── calico-network-policies.yaml
├── terraform
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
└── Jenkinsfile
"# asterisk-codebase-project" 
"# Asterisk-project" 

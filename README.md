# Ansible_wordpress Installation with Ansible

### Prerequisites

#### Package requirements
Webserver
```
Wordpress Version: 5.7.2
PHP version: 7.4 or greater
MySQL Version: 5.6 or greater
MariaDB Version: 10.1 or greater
Apache/2.4.37 (centos)
```
Database
```
Mariadb Server Version: 10.3.29
Mysql Version: 5.6 or greater 
```
#### Server Requirements
Webserver
```
Operating system: CentOS 8
CPU/RAM: 1 /1GB
Storage: 10GB or more
```
Database
```
Operating system: Ubuntu 20.04
CPU/RAM: 1 /1GB
Storage: 10GB or more
```

## Diagram

### Directory Structure
Setup and Manage Wordpress with Ansible
```
.
├── dev_inventory.yml
├── playbook
│   ├── add_ansible_user.yml
│   ├── packages.yml
│   └── ping.yml
└── README.md
```
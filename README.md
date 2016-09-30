# Readme
Install packages contained in the Vagrant Box Version 0.1
--
 1. GNS3 from [GNS3 Ubuntu Installer Guide (repo added to Vagrant Box)](https://gns3.com/support/docs/linux-installation)
 2. Tree
 3. Ansible
 4. Python 3.4.3
 5. Jinja2 for Python

Home Folder Layout
--
```
vagrant@vagrant:~$ tree 
.
├── Desktop
├── Documents
├── Downloads
├── GNS3
│   ├── configs
│   │   └── vpcs_base_config.txt
│   └── projects
│       └── untitled
│           ├── screenshot.png
│           └── untitled.gns3
├── Music
├── Pictures
├── Public
├── Scripts
├── Templates
└── Videos

13 directories, 3 files
vagrant@vagrant:~$ 
```
Ansible Layout
--
```
vagrant@vagrant:/etc/ansible$ tree
.
├── ansible.cfg
└── hosts

0 directories, 2 files
vagrant@vagrant:/etc/ansible$ 
```
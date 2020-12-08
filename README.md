# Simple project for nginx installation and configuration with Ansible
## Project structure:

``` bash
.
├── README.md
├── ansible.cfg                # ansible configuration file
├── data                       # 
│   ├── default                # nginx configuration file
│   └── service_stat           # file with service state message
├── group_vars                 # group variables folder
│   └── STAGING_SERVERS_WEB    # 
├── hosts                      # contain servers addresses
└── playbooks                  #
    ├── playbook_nginx.yaml    # install nginx, start, configure, add cron script, add service_stat file
    ├── playbook_ping.yaml     # ping all servers
    ├── restart_nginx.yaml     # shut down and restart nginx 
    └── uninstall_nginx.yaml   # shut down and uninstall nginx

```

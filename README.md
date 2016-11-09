Installation
------------

    ansible-galaxy install -r requirements.yml

Usage
------------

    ANSIBLE_HOSTS=hosts ansible-playbook consulservers.yml webservers.yml load-balancer.yml

Monitoring
------------

Consul UI
http://xx.xx.xx.xx:8500/ui/#/dc1/services

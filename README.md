# maum_ha_ansible
***
## ansible automation setting for maum_ha

~rpm -Uvh epel-release*rpm~

rpm ansible-2.9.15-1.el7.noarch.rpm
***

ansible-playbook -vv LB_install.yaml
- Load Balancing install. HAProxy, Keepalived

ansible-playbook -vv LB_config.yaml
- Keepalived, HAProxy configure.

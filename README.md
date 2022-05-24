# Ansible-DynamicPlugin-Droplets
Playbook uses the dynamic inventory plugin from DigitalOcean collection to spin up droplets.

Run:
$ ansible-playbook playbook.yml -i do__hosts.yml 

-add as many droplets as you need in the playbook.yml loop without the need to edit the inventory file: do_hosts.yml

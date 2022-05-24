# Ansible-DynamicPlugin-Droplets
Playbook uses the dynamic inventory plugin from DigitalOcean collection to spin up droplets.

Run:
$ ansible-playbook playbook.yml -i do_hosts.yml 

Add as many droplets as you need in the playbook.yml loop without the need to edit the inventory file: do_hosts.yml

To destroy the droplets: change 'state: present' to absent

# Ansible-DynamicPlugin-Droplets
Theory: Playbook uses the dynamic inventory plugin from the DigitalOcean collection to spin up 2 app server droplets.

Run:
$ ansible-playbook playbook.yml -i do_hosts.yml 

To add droplets:  Add them in the playbook.yml loop without the need to edit the inventory file: do_hosts.yml

To destroy droplets: edit the 'Create a new droplet' taske and change 'state: present' to absent.

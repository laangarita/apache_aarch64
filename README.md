Simple Apache web server playbook
This playbook assumes a running RHEL 9.2 aarch64 #
The inventory file should have the IP of the host #

# Run playbook
ansible-playbook -i inventory webservers.yml -K

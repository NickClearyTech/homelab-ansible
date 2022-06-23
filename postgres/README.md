To run, edit [ansible_hosts.txt](ansible_hosts.txt), and edit the hostname
Then, run:
``` sh
ansible-playbook -i ansible_hosts.txt postgres-install.yml -e "db_user=dbuser db_password=dbpassword db_name=dbname"
```
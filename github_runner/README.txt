To run, edit [ansible_hosts.txt](ansible_hosts.txt), and edit the hostname
Then, run:
``` sh
ansible-playbook -i ansible_hosts.txt github-runner-install.yml -e "github_token=TOKEN"
```
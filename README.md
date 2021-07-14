# ansible
My collection of ansible playbooks

## How to
- create a hosts file with any name. ex: playbook_hosts
- look for `# change this` in every file and that you have to change as per your environment
- run the playbook as `ansible-playbook playbook_name.yml -i /path/to/ansible_hosts`

| | Playbook  | Purpose | Notes |
| ------------- | ------------- | ------------- | ------------- |
| 1 | prometheus.node.exporter  | Run prometheus node exporter docker container on a managed node |  |

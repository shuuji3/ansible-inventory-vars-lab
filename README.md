# ansible-inventory-vars-lab

🧪 Ansible inventory vars experiment lab.

## How to play this role

```shell
git clone https://github.com/shuuji3/ansible-inventory-vars-lab
ansible-playbook -i ansible-inventory-vars-lab/hosts ansible-inventory-vars-lab/test-playbook.yml -vv
```

## Results

- [Execution log](results/run-ansible-playbook.log)
- This play creates `/tmp/dhcpd.conf` with [this content](results/dhcpd.conf).

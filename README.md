# ansible-cnetos-monitorix-install

ping hosts
```
ansible -i hosts all -m ping
```
install monitorix
```
ansible-playbook -i hosts monitorix.yml
```

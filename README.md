# 1. Install Ansible
```
apt update
apt install software-properties-common
add-apt-repository --yes --update ppa:ansible/ansible
apt install ansible
```
# 2. Edit inventory and check connection
```
/etc/ansible/hosts
```
```
ansible all -m ping
```

# 3. Run Ansible
### playbook
```
ansible-playbook update.yml
```
```
ansible-playbook update.yml pi.yml docker.yml
```
### command
```
ansible all -m command -a 'uptime -p'
```

# Documentation
https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html#installing-ansible-on-ubuntu

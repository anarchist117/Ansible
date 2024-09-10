# Install Ansible
```
apt update
apt install software-properties-common
add-apt-repository --yes --update ppa:ansible/ansible
apt install ansible
```

# Check connection
```
ansible -i inventory.ini -m ping all
```

# Documentation
https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html#installing-ansible-on-ubuntu

Ansible SRE Tools
=========

### Requirements
**Operacional System:** Deepin distro based in Debian  
Install `Ansible 2.9`  
Dependencies: `python-apt`

```
apt update
apt install software-properties-common
add-apt-repository --yes --update ppa:ansible/ansible
apt install ansible
```

How to execute playbook:
```
$ cd ansible-sre-tools
$ ansible-playbook main.yml
```

Now wait for Ansible to configure your environment.
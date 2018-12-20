Ansible playbooks for juniorctf, see https://framagit.org/axellec/juniorctf

## Prerequisites
### Install the Ansible PPA repository
```bash
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
```

### Install the Ansible package
```bash
$ sudo apt update
$ sudo apt install ansible
```

### Install additional required packages
```bash
$ sudo apt install git python python-pip
```

### Install the mysql and redis roles
```bash
$ ansible-galaxy install geerlingguy.mysql
$ ansible-galaxy install geerlingguy.redis
```

## Running the Playbook
```bash
$ ansible-playbook -K local.yml
```

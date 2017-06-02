
http://docs.ansible.com/ansible/intro_installation.html

    $ sudo apt-get install software-properties-common
    $ sudo apt-add-repository ppa:ansible/ansible
    $ sudo apt-get update
    $ sudo apt-get install ansible

### script connect with a new server

    #!/bin/bash 
    server=$1
    ssh-copy-id  root@$server
    ssh-copy-id  user@$server
    ssh root@$server  "apt-get update;apt-get install python-simplejson"
    ssh root@$server "echo '#add to deploy with ansible' >> /etc/sudoers"
    ssh root@$server "echo '%sudo ALL=NOPASSWD:ALL' >> /etc/sudoers "
    ssh root@$server "echo '%agalan ALL=NOPASSWD:ALL' >> /etc/sudoers "

### install minimal packages

ansible myhost --sudo -m raw -a "yum install -y python python-simplejson"


ansible desks --sudo -m raw -a "apt install -y python python-simplejson"

ssh-copy-id user@domain


### Create a simple project to start

mkdir -p project

cd project

ansible-playbook


### test that is responding

ansible host -m ping

project structure

http://docs.ansible.com/ansible/playbooks_best_practices.html#directory-layout

### Create inventory

http://docs.ansible.com/ansible/intro_inventory.html
create a simple the playbook

#### run the playbook

ansible-playbook -i inventory playbook.yml


### create a role

run the playbook with a role

### Questions  ??














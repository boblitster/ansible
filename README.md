# ansible

Ansible install instructions in bash

 
sudo apt-get update
sudo apt-get install -y libssl-dev libffi-dev python-dev python-pip 
sudo pip install ansible

create new directory

	  mkdir ansible 

cd into new directory

create playbook

	  nano docker-playbook.yml

paste in the code (docker-playbook.yml)

run the playbook

	  ansible-playbook docker-playbook.yml
    
   run docker version 
   
   if this fails then run the docker script from the command line 
   
   ./docker.sh


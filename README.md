## **Pre-requisite**

virtualbox,Vagrant,ansible,vagrant box(generic/ubuntu2002)


1. edit vagrant file for ip and interface 

1. vagrant up

1. cd ansible

1. edit inventory.cfg as per your vagrant machine key path and IP address

1. ansible-playbook -i inventory.cfg playbook.yml

hadoop-centos7-ansible
======================

Install single node Hadoop on CentOS 7 in 5 simple steps with Ansible

See also http://malderhout.wordpress.com/2014/08/22/install-single-node-hadoop-on-centos-7-in-5-simple-steps/

Hadoop user is now changed to vagrant user

Change ip in hosts and Vagrantfile if needed 

## Required:

- VirtualBox
- Vagrant
- Ansible

## Start:

```
$ git clone https://github.com/malderhout/hadoop-centos7-ansible.git
$ cd hadoop-centos7-ansible
$ vagrant up

```

## Test:

http://localhost:50070/ 

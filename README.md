# mesos-vagrant

Like-production environment to be executed locally (Zookeeper, Mesos and Marathon)


## Dependencies

You need to install:

* [Vagrant](https://www.vagrantup.com/)
* A Vagrant provider to run virtual machines (i.e. [VirtualBox](https://www.virtualbox.org/))
* [Ansible](https://www.ansible.com/)
* Python

## Clone the repository

```bash
$ git clone git@github.com:mendrugory/mesos-vagrant.git
$ cd mesos-vagrant
```

## Start up the virtual machines

```
$ vagrant up
```

## Configure the virtual machines

```
$ ansible-playbook mesos.yml
```

You can read a little bit more [here](https://www.mendrugory.com/post/mesos-local-development)
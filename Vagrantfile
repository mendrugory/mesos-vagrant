# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|

  config.vm.define "mesos1" do |mesos1|
    mesos1.vm.hostname = "mesos1"
    mesos1.vm.box = "ubuntu/trusty64"
    mesos1.vm.network "private_network", ip: "192.168.33.11" 
  end

  config.vm.define "mesos2" do |mesos2|
    mesos2.vm.hostname = "mesos2"
    mesos2.vm.box = "ubuntu/trusty64"
    mesos2.vm.network "private_network", ip: "192.168.33.12" 
  end

  config.vm.define "mesos3" do |mesos3|
    mesos3.vm.hostname = "mesos3"
    mesos3.vm.box = "ubuntu/trusty64"
    mesos3.vm.network "private_network", ip: "192.168.33.13"
  end

end
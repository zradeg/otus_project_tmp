# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"
  config.vbguest.iso_path = "../VBoxGuestAdditions.iso"
  config.vm.provider "virtualbox" do |v|
	  v.memory = 512
  end

#  config.vm.define "ngx01" do |ngx01|
#    ngx01.vm.network "private_network", ip: "192.168.11.111", virtualbox__intnet: false
#    ngx01.vm.hostname = "ngx01"
#  end
#
#  config.vm.define "ngx02" do |ngx02|
#    ngx02.vm.network "private_network", ip: "192.168.11.112", virtualbox__intnet: false
#    ngx02.vm.hostname = "ngx02"
#  end
#
#  config.vm.define "postfix01" do |postfix01|
#    postfix01.vm.network "private_network", ip: "192.168.11.113", virtualbox__intnet: false
#    postfix01.vm.hostname = "postfix01"
#  end
#
#  config.vm.define "postfix02" do |postfix02|
#    postfix02.vm.network "private_network", ip: "192.168.11.114", virtualbox__intnet: false
#    postfix02.vm.hostname = "postfix02"
#  end
#
#  config.vm.define "postfix03" do |postfix03|
#    postfix03.vm.network "private_network", ip: "192.168.11.115", virtualbox__intnet: false
#    postfix03.vm.hostname = "postfix03"
#  end
#
#  config.vm.define "proxysql01" do |proxysql01|
#    proxysql01.vm.network "private_network", ip: "192.168.11.116", virtualbox__intnet: false
#    proxysql01.vm.hostname = "proxysql01"
#  end

  config.vm.define "pxc1" do |pxc1|
    pxc1.vm.network "private_network", ip: "192.168.11.120", virtualbox__intnet: false
    pxc1.vm.hostname = "pxc1"
  end

  config.vm.define "pxc2" do |pxc2|
    pxc2.vm.network "private_network", ip: "192.168.11.121", virtualbox__intnet: false
    pxc2.vm.hostname = "pxc2"
  end

  config.vm.define "pxc3" do |pxc3|
    pxc3.vm.network "private_network", ip: "192.168.11.122", virtualbox__intnet: false
    pxc3.vm.hostname = "pxc3"
  end
#
#  config.vm.define "backup" do |backup|
#    backup.vm.network "private_network", ip: "192.168.11.123", virtualbox__intnet: false
#    backup.vm.hostname = "backup"
#  end

#  config.vm.provision "ansible" do |ansible|
#    ansible.verbose = "v"
#    ansible.playbook = "playbook.yml"
#    ansible.become = "true"
#  end


end
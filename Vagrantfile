# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.define "proxy" do |s|
    s.vm.box = "centos/7"
    s.vm.network "private_network", ip: "10.100.0.11"
    s.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
    end
    s.ssh.insert_key = false
    s.ssh.private_key_path = ["~/.vagrant.d/insecure_private_key"]
  end

  config.vm.define "api1" do |s|
    s.vm.box = "centos/7"
    s.vm.network "private_network", ip: "10.100.0.12"
    s.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
    end
    s.ssh.insert_key = false
    s.ssh.private_key_path = ["~/.vagrant.d/insecure_private_key"]
  end

  config.vm.define "api2" do |s|
    s.vm.box = "centos/7"
    s.vm.network "private_network", ip: "10.100.0.13"
    s.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
    end
    s.ssh.insert_key = false
    s.ssh.private_key_path = ["~/.vagrant.d/insecure_private_key"]
  end

end
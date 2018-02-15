# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.box_check_update = false 
  config.vm.network "private_network", ip: "10.100.0.10"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
  end
  # config.vm.provision "shell", inline: <<-SHELL
  #  yum update -y
  #  yum install epel-release -y
  #  yum install -y nginx net-tools
  #  systemctl start nginx
  #  echo "Hello #1" > /usr/share/nginx/html/index.html
  #  sudo chown root:root /usr/share/nginx/html/index.html
  #  echo "Provisioning Complete!"
  # SHELL
end

# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
 
  config.vm.box = "hashicorp/bionic64"

  config.vm.hostname = "bionicNode"

  config.vm.provision :shell, path: "vagrant_provis/bootstrap.sh"
end

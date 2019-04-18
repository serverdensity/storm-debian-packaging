# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.define "ubuntu" do |m|
      m.vm.box = "ubuntu/trusty64"
      m.vm.provision "shell", path: "bootstrap.sh"
  end
end

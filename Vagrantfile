# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "debian/jessie64"

  #forward guest's 8080 port on hosts 8090
  config.vm.network "forwarded_port", guest: 8080, host: 8090
end

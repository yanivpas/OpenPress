# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
 
  # Every Vagrant virtual environment requires a box to build off of.
  config.vm.box = "base"

  # load basic vagrant ubuntu
  config.vm.box = "precise32"

  config.vm.provision :shell, :path => "./vagrant/get-pip.py"

  config.vm.provision :shell, :path => "./vagrant/bootstrap.sh"
end

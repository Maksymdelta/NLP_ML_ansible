# -*- mode: ruby -*-
# vi: set ft=ruby :
VAGRANTFILE_API_VERSION = "2"
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.network :private_network, ip:"192.168.200.100"
  # Guest to Host
  #config.vm.synced_folder "/Users/ohgushimasaya/Desktop/Study/MachineLearning_Python/machine_learning_ansible/code", "/home/vagrant/positive_negative",
  #type: "rsync_pull",
  #rsync__exclude: ["20news-bydate-test/", "20news-bydate-train/"]
  # Host to Guest
  config.vm.synced_folder "/Users/ohgushimasaya/Desktop/Study/MachineLearning_Python/machine_learning_ansible/code", "/home/vagrant/positive_negative", 
  type: "rsync"
#  config.vm.provider "virtualbox" do |v|
#     v.memory = 1524
#  end
end

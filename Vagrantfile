Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.network "public_network", bridge: "wlo1"
    config.vm.provider "virtualbox" do |vm|
      vm.name = "virtualbox-ubuntu"
      vm.memory = 1024
      vm.cpus = 2
    end
end
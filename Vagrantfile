# -*- mode: ruby -*-
# vi: set ft=ruby :


nodes = [
  { :hostname => 'client1', :ram => 2048}
]
Vagrant.configure("2") do |config|
  nodes.each do |node|
    config.vm.define node[:hostname] do |nodeconfig|
      nodeconfig.vm.box = "ubuntu/xenial64"
      nodeconfig.vm.hostname = node[:hostname]
      nodeconfig.vm.network "public_network"
   #   nodeconfig.vm.provision "ansible", type: "ansible", playbook: "vagrant.yml", verbose: "-vv"
   #   end
    end
  end
end
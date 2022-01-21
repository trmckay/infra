# -*- mode: ruby -*-
# vi: set ft=ruby :
#
Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu2004"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "dev-box.yml"
    ansible.become_user = "root"
  end
end

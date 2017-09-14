# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip: "192.168.33.13"
  #config.vm.synced_folder "./laravel", "/var/www/laravel"
  
  config.vm.provider "virtualbox" do |vb|
    vb.name = "study_laravel"
  end

  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "./ansible/playbook.yml"
  end

end

# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  
  # Use this link to download base box image:  https://vagrantcloud.com/ubuntu/boxes/trusty64/versions/14.04/providers/virtualbox.box
  # And set the environment variable 'vagrant_base_box_url' to the path of box image
  config.vm.box = "my-vagrant-box"
  config.vm.box_url = ENV['vagrant_base_box_url'] 
 
  config.vm.network "private_network", ip: "192.168.33.10"
end

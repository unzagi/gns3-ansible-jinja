# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # All Vagrant configuration is done here. The most common configuration
  # options are documented and commented below. For a complete reference,
  # please see the online documentation at vagrantup.com.

  # Every Vagrant development environment requires a box to build off of.
  config.vm.box_url = "https://atlas.hashicorp.com/unzagi/boxes/ubuntu-desktop/"
  config.vm.box = "unzagi/ubuntu-desktop"
  
 
  
  # Sync between the web root of the VM and the 'configs' directory
  config.vm.synced_folder "configs/", "/home/vagrant/vagrantGNS3/configs/"
  # Sync between the web root of the VM and the 'projects' directory
  config.vm.synced_folder "projects/", "/home/vagrant/vagrantGNS3/projects/"
    # Sync between the web root of the VM and the 'images' directory
  config.vm.synced_folder "images/", "/home/vagrant/vagrantGNS3/images/"
    # Sync between the web root of the VM and the 'projects' directory
  config.vm.synced_folder "projects/", "/home/vagrant/vagrantGNS3/projects/"
  # Sync between the scripts foldr in the VM and the 'scripts' directory
  config.vm.synced_folder "scripts/", "/home/vagrant/scripts/"
  # Sync between the web root of the VM and the 'ansible' directory
  config.vm.synced_folder "ansible/", "/etc/ansible", mount_options: ["fmode=666"]

  config.vm.provider :virtualbox do |vb|
    vb.customize ['modifyvm', :id, '--usb', 'on']
  end
  
end

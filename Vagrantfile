# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure("1") do |config|
  config.vm.boot_mode = :gui
end

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "udacity/ud381"
  config.vm.network :forwarded_port, guest: 5000, host: 5000
  config.vm.boot_timeout = 500
end

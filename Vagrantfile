# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.define "gitlab" do |gitlab|
    gitlab.vm.box = "ubuntu/xenial64"
    gitlab.vm.network "private_network", ip: "192.168.201.20"
    gitlab.vm.hostname = "gitlab"

    config.vm.provider "virtualbox" do |vb|
      vb.memory = "4096"
      vb.cpus = "4"
    end

  end
end

# -*- mode: ruby -*-
# vi: set ft=ruby :
for crating multi vms
Vagrant.configure("2") do |config|
  config.vm.define "server" do |server|
  server.vm.box = "centos/7"
 server.vm.network "private_network", ip: "192.168.56.100"
 server.vm.hostname = "server"

end

 config.vm.define "client" do |client|
 client.vm.box = "hashicorp/precise64"
 client.vm.network "private_network", ip: "192.168.55.110"
 client.vm.hostname = "client"
end
end


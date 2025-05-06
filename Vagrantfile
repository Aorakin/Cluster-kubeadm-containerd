Vagrant.configure("2") do |config|
  config.vm.define "master" do |master|
    master.vm.box = "ubuntu/jammy64"
    master.vm.hostname = "master"
    master.vm.network "private_network", ip: "192.168.56.10"
    config.vm.network "public_network", bridge: "Killer(R) Wi-Fi 6 AX1650i 160MHz Wireless Network Adapter (201NGW)"
    master.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
    end
  end

  config.vm.define "worker1" do |worker|
    worker.vm.box = "ubuntu/jammy64"
    worker.vm.hostname = "worker1"
    worker.vm.network "private_network", ip: "192.168.56.11"
    config.vm.network "public_network", bridge: "Killer(R) Wi-Fi 6 AX1650i 160MHz Wireless Network Adapter (201NGW)"
    worker.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
    end
  end
end

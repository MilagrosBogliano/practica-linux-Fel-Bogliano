=========MAQUINA FEL Y BOGLIANO=========
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.vm.hostname = "linux-practice"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = 2

    unless File.exist?('./disk1.vdi')
      vb.customize ['createhd', '--filename', './disk1.vdi', '--size', 1024]
    end

    vb.customize ['storageattach', :id, '--storagectl', 'SCSI', '--port', 2, '--device', 0, '--type', 'hdd', '--medium', './disk1.vdi']
  end

  config.vm.network "private_network", ip: "192.168.56.10"
  config.vm.network "forwarded_port", guest: 8080, host: 8080
  config.vm.network "forwarded_port", guest: 5353, host: 5353, protocol: "udp"

  config.vm.provision "shell", inline: <<-SHELL
    apt-get update
    apt-get install -y neofetch git docker.io docker-compose
    usermod -aG docker vagrant
    systemctl enable docker
    systemctl start docker
  SHELL
end

=========MAQUINA TERCER PERSONA=========
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.vm.hostname = "linux-practice"

  config.vm.provider "virtualbox" do |vb|
    vb.name = 'maquina-3-compa'
    vb.memory = "2048"
    vb.cpus = 2

    unless File.exist?('./disk1.vdi')
      vb.customize ['createhd', '--filename', './disk1.vdi', '--size', 1024]
    end

    vb.customize ['storageattach', :id, '--storagectl', 'SCSI', '--port', 2, '--device', 0, '--type', 'hdd', '--medium', './disk1.vdi']
  end

  config.vm.network "private_network", ip: "192.168.56.10"
  config.vm.network "forwarded_port", guest: 8080, host: 8081
  config.vm.network "forwarded_port", guest: 5353, host: 5353, protocol: "udp"

  config.vm.provision "shell", inline: <<-SHELL
    apt-get update
    apt-get install -y neofetch git docker.io docker-compose
    usermod -aG docker vagrant
    systemctl enable docker
    systemctl start docker
  SHELL
end



Vagrant.configure(2) do |config|
   #Pour toute les machine qui fonctionne avec virtualbox
   config.vm.provider "virtualbox" do |vb|
    vb.memory = "512" 
  end

  #Configuration de la VM "VM1"
  config.vm.define "VM1" do |machine|
    machine.vm.box = "centos"   #Nom de la box utilisée
    machine.vm.hostname = "TestVM1"     #Hostname de la VM
    machine.vm.network :private_network, ip: "192.168.10.191"   #Création d'un réseau privé avec l'ip mentionné 
  end

  #Configuration de la VM "VM2"
  config.vm.define "VM2" do |machine|
    machine.vm.box = "centos"    #Nom de la box utilisée
    machine.vm.hostname = "TestVM2"      #Hostname de la VM
    machine.vm.network :private_network, ip: "192.168.10.192"   ##Création d'un réseau privé avec l'ip mentionné
  end
end
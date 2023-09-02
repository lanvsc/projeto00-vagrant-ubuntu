Vagrant.configure("2") do |config|
  #Configurando VM
  config.vm.define:proj00 do |proj00_config|
    proj00_config.vm.box = "bento/ubuntu-22.04"
    proj00_config.vm.network "public_network"
    proj00_config.vm.provider "virtualbox" do |v|
      v.gui = true
      v.memory = "1024"
      v.cpus = "1"
    end
  end
end    
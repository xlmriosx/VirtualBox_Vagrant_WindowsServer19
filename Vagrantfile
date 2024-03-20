Vagrant.configure("2") do |config|
    config.vm.box = "gusztavvargadr/windows-server-2019-standard"
  
    config.vm.provider "virtualbox" do |vb|
      vb.memory = "12288" # 12GB de RAM
      vb.cpus = 4 # 4 CPUs
    end
  
    config.vm.provider "virtualbox" do |vb|
      vb.customize ["modifyvm", :id, "--vram", "100"] # 100GB de espacio en disco
    end
  
    config.vm.synced_folder "C:/BI", "/BI"
    config.vm.boot_timeout = 3000
end
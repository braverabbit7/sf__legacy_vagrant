Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/trusty64"
    
    config.vm.provision "shell", inline: <<-SHELL

     sudo apt-get -y update && apt-get upgrade
     apt-get -y install postgresql-9.3
    
      
    SHELL
  end
  
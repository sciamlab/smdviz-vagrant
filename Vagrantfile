Vagrant.configure("2") do |config|
   config.vm.box = "smdviz"
   config.vm.network "private_network", ip: "10.0.0.2"
   config.vm.host_name = "smdviz.sciamlab.local"
   config.vm.provider "virtualbox" do |vb|
     vb.customize ["modifyvm", :id, "--memory", "4096"]
     vb.customize ["modifyvm", :id, "--cpus", "2"]  
   end
end

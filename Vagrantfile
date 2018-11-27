Vagrant.configure("2") do |config|
  
    config.vm.define vm_name="web01" do |node|
    config.vm.network "forwarded_port", guest: 80, host: 8080, auto_correct: true
      node.vm.box = "nikcbg/nginx64"
      node.vm.hostname = vm_name
    config.vm.network "private_network", ip: "192.168.56.56"
 end
  
    config.vm.define vm_name="web02" do |node|
    config.vm.network "forwarded_port", guest: 80, host: 8080, auto_correct: true
      node.vm.box = "nikcbg/nginx64"
      node.vm.hostname = vm_name
    config.vm.network "private_network", ip: "192.168.56.57"
   end
 end


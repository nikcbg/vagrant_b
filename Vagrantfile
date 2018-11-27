Vagrant.configure("2") do |config|

  (1..2).each do |i|
    config.vm.define vm_name="web0#{i}" do |node|
    config.vm.network "forwarded_port", guest: 80, host: 8080,
      auto_correct: true
      node.vm.box = "nikcbg/nginx64"
      node.vm.hostname = vm_name
    end
  end
end

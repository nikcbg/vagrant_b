Vagrant.configure("2") do |config|

  (01..02).each do |i|
    config.vm.define vm_name="web#{i}" do |node|
      node.vm.box = "nikcbg/nginx64"
      node.vm.hostname = vm_name
    end
  end
end

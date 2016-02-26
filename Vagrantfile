Vagrant.configure(2) do |config|
  config.vm.box = "alvaro/jessie"
  config.vm.hostname = "jessie-go16"
  config.vm.provision "shell", path: "scripts/provision.sh" , privileged: false
end

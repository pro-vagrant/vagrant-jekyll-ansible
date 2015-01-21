VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty32"
  config.vm.network :forwarded_port, guest: 4000, host: 8080, host_ip: "127.0.0.1"
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "playbook.yml"
  end
end

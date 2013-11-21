VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

    # Base machine of a 32 bit Ubuntu 12.04 image.
    config.vm.box = "precise32"
    config.vm.box_url = "http://files.vagrantup.com/precise32.box"

    # Access port 8000 on the guest from port 8000 on the host.
    config.vm.network "forwarded_port", guest: 8000, host: 8000

    # Use Puppet to provision the machine.
    config.vm.provision "puppet"

end
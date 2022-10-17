Vagrant.configure("2") do |config|
	config.vm.define "my-centos-8" do |acs|
		acs.vm.box = "centos/8"
		acs.vm.hostname = "my-centos-8"
		acs.vm.network "private_network", ip:"192.168.33.10"
	end
end
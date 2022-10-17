Vagrant.configure("2") do |config|
	config.vm.define "my-centos-8" do |my-centos-8|
		my-centos-8.vm.box = "centos/8"
		my-centos-8.vm.hostname = "my-centos-8"
		my-centos-8.vm.network "private_network", ip:"192.168.33.10"
	end
end
Vagrant.configure("2") do |config|
config.vm.define "10.11.13.50" do |vm1|
vm1.vm.box = "bento/ubuntu-22.04"
vm1.vm.box_download_insecure = true
vm1.vm.hostname = '10.11.13.50'
vm1.vm.box_url = "bento/ubuntu-22.04"
vm1.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)", auto_config: false
vm1.vm.network "forwarded_port", guest: 22, host: 2322
vm1.vm.network :private_network, ip: "10.11.13.50"
end
# config.vm.define "10.11.13.51" do |vm2|
# vm2.vm.box = "bento/ubuntu-22.04"
# vm2.vm.box_download_insecure = true
# vm2.vm.hostname = '10.11.13.51'
# vm2.vm.box_url = "bento/ubuntu-22.04"
# vm2.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)", auto_config: false
# vm2.vm.network "forwarded_port", guest: 22, host: 3322
# vm2.vm.network :private_network, ip: "10.11.13.51"
# end
# config.vm.define "10.11.13.52" do |vm3|
# vm3.vm.box = "bento/ubuntu-22.04"
# vm3.vm.box_download_insecure = true
# vm3.vm.hostname = '10.11.13.52'
# vm3.vm.box_url = "bento/ubuntu-22.04"
# vm3.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)", auto_config: false
# vm3.vm.network "forwarded_port", guest: 22, host: 4322
# vm3.vm.network :private_network, ip: "10.11.13.52"
# end
# config.vm.define "10.11.13.53" do |vm4|
# vm4.vm.box = "bento/ubuntu-22.04"
# vm4.vm.box_download_insecure = true
# vm4.vm.hostname = '10.11.13.53'
# vm4.vm.box_url = "bento/ubuntu-22.04"
# vm4.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)", auto_config: false
# vm4.vm.network "forwarded_port", guest: 22, host: 5322
# vm4.vm.network :private_network, ip: "10.11.13.53"
# end
end

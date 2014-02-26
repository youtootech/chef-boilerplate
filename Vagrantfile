Vagrant::Config.run do |config|
  config.vm.box_url = "http://puppet-vagrant-boxes.puppetlabs.com/centos-64-x64-vbox42http://puppet-vagrant-boxes.puppetlabs.com/centos-64-x64-vbox4210.box
   config.vm.provision :chef_solo do |chef|
     chef.cookbooks_path = "cookbooks"
     # chef.add_recipe "redis"
     chef.log_level = :debug
  end 
end

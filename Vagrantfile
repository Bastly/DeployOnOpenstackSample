require 'vagrant-openstack-provider'

Vagrant.configure('2') do |config|

  config.vm.box       = 'openstack'
  config.ssh.username = 'stack'

  config.vm.provider :openstack do |os|
    os.openstack_auth_url = 'http://192.168.1.201:5000/v2.0/tokens'
    os.username           = 'deployer'
    os.password           = 'deployer'
    os.tenant_name        = 'deployment'
    os.flavor             = 'm1.small'
    os.image              = 'Ubuntu64'
    os.floating_ip_pool   = 'public'
  end
end
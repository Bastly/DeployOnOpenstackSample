# DeployOnOpenstackSample
Project sample to deploy on openstack our infraestructure.

# Install openstack provider
    vagrant plugin install vagrant-openstack-provider

# start instance
    vagrant up --provider=openstack
  
# create dummy openstack box
    tar cvzf openstack.box ./metadata.json ./Vagrantfile
    
# reference doc
https://github.com/ggiamarchi/vagrant-openstack-provider

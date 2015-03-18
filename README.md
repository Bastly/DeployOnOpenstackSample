# DeployOnOpenstackSample
Project sample to deploy on openstack our infraestructure.

# Install openstack provider
    vagrant plugin install vagrant-openstack-provider

# start instance
    vagrant up --provider=openstack
  
# create dummy openstack box
    tar cvzf openstack.box ./metadata.json ./Vagrantfile

#images loaded in openstack
http://docs.openstack.org/image-guide/content/ch_obtaining_images.html
Can be downloaded from ubuntu cloud
http://cloud-images.ubuntu.com/trusty/current/
Scroll to the bottom and get a disk1.img of AMD64, then load them into glance via web selecting AMI type.


# reference doc
https://github.com/ggiamarchi/vagrant-openstack-provider

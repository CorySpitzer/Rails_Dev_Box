## A Rails Development Box
### By Cory Spitzer
##### *MIT License*

Need an environment to develop a Rails app with a Postgres DB? Spin up this vagrant box, provision it with the Ansible scripts and you should be all set!

#### Dependencies - built and tested with:
  * [Vagrant 1.7.4](https://www.vagrantup.com/download-archive/v1.7.4.html)
  * [VirtualBox 4.3](https://www.virtualbox.org/wiki/Download_Old_Builds) and you might want VirtualBox GuestAdditions

#### Detailed instructions:
  0. Make sure that you have the dependencies installed on your host machine (see links above)
  1. `cd` into the root of the Rails_Dev_Directory so that we are in the same directory as the `Vagrantfile` and run 'vagrant up'. This will download the box, and may take a while depending on network speed.
  2. Make sure you can enter the guest virtual machine with `vagrant ssh` (control-d or similar will get you out of the guest)
  3. Run the Ansible playbooks with ``


*Under Construction*

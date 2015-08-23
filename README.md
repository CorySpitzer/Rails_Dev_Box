## Rails Box: A Rails Development Box
### By Cory Spitzer
##### *MIT License*

Need an environment to develop a Rails app with a Postgres DB? Spin up this vagrant box, provision it with the Ansible scripts and you should be all set!

#### Dependencies - built and tested with:
  * [Vagrant 1.7.4](https://www.vagrantup.com/download-archive/v1.7.4.html)
  * [VirtualBox 4.3](https://www.virtualbox.org/wiki/Download_Old_Builds) and you might want VirtualBox GuestAdditions

#### Detailed instructions:
  <!-- The repeated ones do automatic numbering in Markdown: -->
  1. Make sure that you have the dependencies installed on your host machine (see links above)
  1. Clone the repo, `git clone https://github.com/CorySpitzer/Rails_Dev_Box.git`, and `cd` into the root of the Rails_Dev_Directory so that we are in the same directory as the `Vagrantfile`.
  1. Start the guest machine with 'vagrant up'. When this is run the first time it will download the box, which may take a while, and run the `setup.yml` playbook, which may also take while.
  1. Make sure you can enter the guest virtual machine with `vagrant ssh` (control-d or similar will get you out of the guest). In the guest terminal that it opens you can verify that Ruby 2.0 is install by running `vagrant@vagrant: ruby2.0 -v`


***

Want to make your own Vagrant boxes and Ansible scripts? Check out [this tutorial](https://adamcod.es/2014/09/23/vagrant-ansible-quickstart-tutorial.html)

*Under Construction*

# vagrant-centos68-i686-box
A vagrant CentOS 6.8 i686 base box

This project was created to share with you the Vagrant Base box I created.

Box specifications:
===================

- Operating System: CentOS
- Version: 6.8
- Architecture: i686 (32 bit)
- Packages: mimimal + nano + wget + yum update 'Wednesday, 8 June 2016'
- Provider: VirtualBox
- URL: https://www.dropbox.com/s/vq9ltfnagtaney4/centos68-i686-20160608.box
- Users:  'vagrant' with password 'vagrant' & 'root' with password 'vagrant'

Usage:
======

1. Get the Vagrantfile
2. cd to the directory containing the Vagrantfile
3. run `vagrant up`

Then you can ssh to the VM by running `vagrant ssh`

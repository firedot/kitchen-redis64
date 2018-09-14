# kitchen-redis64
Kitchen-vagrant test for Vagrant box

##Prerequisites: 
* [VirtualBox](https://www.virtualbox.org/manual/ch02.html)
* [Vagrant](https://www.vagrantup.com/downloads.html)

**This repository contains instructions how to perform
kitchen-vagrant test on the box built from this repository: 
[git](git@github.com:firedot/packer-redis64.git)**

1. Follow the instructions from the repository quoted above. 
2. Once the process is completed, run the following command: 
````
vagrant box add --name redis64 redis64.box
````
** This will make the box created with packer available to vagrant**
   * 2.1 Another way to obtain the box is by executing the following command: 
   
     ````
      vagrant box add firedot/redis64
     ````
      The previous line will download the already built box from the VagrantCloud. 
3. Install kitchen by installing the [ChefDK](https://downloads.chef.io/chefdk)
4. Go into the directory where you cloned this repository


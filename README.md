# Vagrant boxes

This repository contains several _Vagrantfiles_ that I use to easily spin up virtual machines.

## Requirements

### Vagrant

You can install _Vagrant_ in many different ways, but if you're not sure what you're doing, browse into the [Vagrant download page](https://www.vagrantup.com/downloads) and follow the instructions.

### Virtualbox

You need _Virtualbox_ if you're planning to use any of these _Vagrantfiles_ on GNU/Linux, MS Windows or macOS. Checkout the [Virtualbox download page](https://www.virtualbox.org/wiki/Downloads).

### Parallels

You need to purchase and install [Parallels](https://www.parallels.com/) if you are planning to use the _Vagrantfiles_ of the macOS boxes.

You also need to install the [Vagrant Parallels Provider](https://github.com/Parallels/vagrant-parallels) plugin for _Vagrant_.

## Using the _Vagrantfiles_

cd-into the folder of the box you want to spin up and run `vagrant up`

If you are familiar with _Vagrant_ you know that you can manage the boxes and interact with _Vagrant_ from the command line. If you're not, check the [cli documentation](https://www.vagrantup.com/docs/cli). Also, you can take a look at this [cheat sheet](https://gist.github.com/wpscholar/a49594e2e2b918f4d0c4).

## Want to contribute?

Feel free to submit your _Vagrantfiles_ in PRs, I'll be happy to include them in the repo.
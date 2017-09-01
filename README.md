# SR388
[![Build Status](https://img.shields.io/travis/mikepadge/SR388.svg?style=flat-square)](https://travis-ci.org/mikepadge/SR388)

DevToolbox w/ interchangeable parts for var pipeline pieces

I get the feeling that the folder structure here is going to be moved around
quite a bit before I'm satisfied with the layout and what should be included. Slash versioned separately. Will break apart in the future as it makes sense and is necessary.

## Currently in the box and being added

Going to try and separate these out into workflows by real world use case
project models. The goal is to define best practice in the architecture of the workflows themselves.

# For Example

- VLAN/VPC


- create ansible role for installing the pre-reqs
* [Ansible](http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip) >= 2.3.2
* [Virtualbox](https://www.virtualbox.org/wiki/Downloads) >= 5.1
* [Vagrant](https://www.vagrantup.com/downloads.html) >= 1.8.5
* [vagrant-bindfs](https://github.com/gael-ian/vagrant-bindfs#installation) >= 0.3.1 (Windows users may skip this)
* [vagrant-hostmanager](https://github.com/smdahlen/vagrant-hostmanager#installation)
* [vagrant-omnibus](https://github.com/chef/vagrant-omnibus#installation)
* [Packer]()
* [Terraform]()

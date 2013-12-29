---
layout: posts
title: Packer Builds AMI's
desc: Packer automates the building of Amazon Machine Images...on Amazon;
permalink: /post/packer-will-build-your-ami.html
shortdesc: yesterday was my first day of furlough in the 2013 government shutdown. during the day i did the following things
category: virtualmachines
tags: 
  - virtualmachines
  - aws
  - ami
published: true
------

I have been working with vagrant for close to year. Today I tried Mitchell Hashimoto's latest project, Packer. 

Vagrant automates the launching and configuration of virtual machines. Vagrant provides virtualized environments that are nearly identical to production environments solving the pain point code working on develop machines but failing in production.

Packer automates the creation of creation of virtual machines. Packer solves the pain point creating a custom virtual machine base box for vagrant. 

To put it painly, packer will build your AMI. 


---
layout: page
title: About
permalink: /about/
published: true
---

The idea of Calamares arose from a desire of several independent Linux distributions to come together and work on a shared system installer. Instead of everyone working on their own implementation and forking forks of forks, why not work together on something that can be used by many?

## What is Calamares

Calamares is an installer framework. By design it is very customizable, in order to satisfy a wide variety of needs and use cases.

Calamares aims to be easy, usable, beautiful, pragmatic, inclusive and distribution-agnostic.

Calamares includes an advanced partitioning feature, with support for both manual and automated partitioning operations. It is the first installer with an automated "Replace Partition" option, which makes it easy to reuse a partition over and over for distribution testing.

Got a Linux distribution but no system installer? [Grab Calamares](https://github.com/calamares/calamares), mix and match any number of [Calamares modules](https://github.com/calamares/calamares/tree/master/src/modules) (or write your own in Python or C++), throw together some [branding](https://github.com/calamares/calamares/tree/master/src/branding), package it up and you are ready to ship!

## What Calamares is not

Calamares is not a Manjaro Linux installer, or a KaOS installer, or a Maui installer, or even an installer for Arch Linux based distributions. Calamares is an independent product. The Calamares team works closely with Linux distributors to provide the very best experience to their users.

Calamares does not aim to be the ultimate "standard" installer of the Linux desktop. Many distributions already have more mature system installer solutions, but some don't, and that's where Calamares can be of use.

## Who develops Calamares

Calamares is maintained by [the Calamares team]({{ site.url }}/team/). Most of us are also [KDE](http://kde.org) developers, and we have received contributions from [BBQLinux](http://bbqlinux.org/), [Fedora](https://fedoraproject.org/), [KaOS](http://kaosx.us/), [Kubuntu](http://kubuntu.org), [Manjaro](http://manjaro.org/), [Maui](http://www.maui-project.org/), [Netrunner](http://www.netrunner.com/) and [OpenMandriva](https://www.openmandriva.org/) developers as well.

We gladly accept contributions from everyone, and we have no exclusive association with any Linux distribution. Calamares is not a KDE project, or a KaOS project, or a Manjaro project, we are just a bunch of people dumping some code on [GitHub](https://github.com/calamares).

## Who ships Calamares

Many Linux distributions are in varying stages of adopting Calamares as their primary system installer.

Operating systems that already ship Calamares:

- [Apricity OS](http://www.apricityos.com/)
- [BBQLinux](http://bbqlinux.org/)
- [BlackPanther OS](http://www.blackpantheros.eu/)
- [Chakra](https://chakraos.org/)
- [Kannolo](https://kannolo.sourceforge.io/) (Fedora Remix)
- [KaOS](http://kaosx.us/)
- [Kogaion](http://rogentos.ro/)
- [Manjaro](http://manjaro.org/)
- [Netrunner](http://www.netrunner.com/)
- [OpenMamba](http://openmamba.org/en/)
- [OpenMandriva](https://www.openmandriva.org/)
- [Pisi Linux](https://pisilinux2.wordpress.com/)
- [Sabayon](https://www.sabayon.org/)
- [Tanglu](http://tanglu.org/)

Operating systems that are evaluating Calamares in pre-release builds:

- [Maui](http://www.maui-project.org/)
- [PCLinuxOS](http://www.pclinuxos.com/)

Operating systems that ship Calamares in their package repositories for third-party derivatives to use:

- [Fedora](https://fedoraproject.org/)

## What is Calamares made of

Calamares is mostly written in C++11, with Qt 5 as general purpose library and UI toolkit.

Calamares is modular by design, and Python 3 was chosen as the main scripting language. The Python 3 interface is implemented with Boost.Python, and all Calamares configuration is done in YAML.

For a complete list of dependencies, see [the README file](https://github.com/calamares/calamares/blob/master/README.md).

## Contact us

IRC: #calamares on chat.freenode.net.  
Mailing list: [calamares-dev@googlegroups.com](mailto:calamares-dev@googlegroups.com)  
Bugs: [Calamares bugs and feature requests](http://calamares.io/bugs)

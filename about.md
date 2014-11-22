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

Got a Linux distribution but no system installer? [Grab Calamares](https://github.com/calamares/calamares), mix and match any number of [Calamares modules](https://github.com/calamares/calamares/tree/master/src/modules) (or write your own in Python or C++), throw together some [branding](https://github.com/calamares/calamares/tree/master/src/branding), package it up and you are ready to ship!

## What Calamares is not

Calamares is not a Manjaro Linux installer, or a KaOS installer, or a Maui installer, or even an installer for Arch Linux based distributions. Calamares is an independent product. The Calamares team works closely with Linux distributors to provide the very best experience to their users.

Calamares does not aim to be the ultimate "standard" installer of the Linux desktop. Many distributions already have more mature system installer solutions, but some don't, and that's where Calamares can be of use.

## Who develops Calamares

Calamares is maintained by [the Calamares team]({{ site.url }}/team/). Most of us are also [KDE](http://kde.org) developers, and we have received contributions from [BBQLinux](http://bbqlinux.org/), [Fedora](https://fedoraproject.org/), [KaOS](http://kaosx.us/), [Kubuntu](http://kubuntu.org), [Manjaro](http://manjaro.org/), [Maui](http://www.maui-project.org/) and [Netrunner](http://www.netrunner-os.com/) developers as well.

We gladly accept contributions from everyone, and we have no exclusive association with any Linux distribution. Calamares is not a KDE project, or a KaOS project, or a Manjaro project, we are just a bunch of people dumping some code on [GitHub](https://github.com/calamares).

## What is Calamares made of

Calamares is mostly written in C++11, with Qt 5 as general purpose library and UI toolkit.

Calamares is modular by design, and Python 3 was chosen as the main scripting language. The Python 3 interface is implemented with Boost.Python, and all Calamares configuration is done in YAML.

For a complete list of dependencies, see [the README file](https://github.com/calamares/calamares/blob/master/README.md).

## Contact us

IRC: #calamares on chat.freenode.net.  
Mailing list: [calamares-dev@googlegroups.com](mailto:calamares-dev@googlegroups.com)  
Bugs: [Calamares issues on GitHub](https://github.com/calamares/calamares/issues)
# How to build a Laravel development environment

My personal notes on creating a local Laravel development environment.

## Table of Contents
* [Laravel Homestead](#laravel-homestead)
  * [macOS](#macos)
    * [Prerequisites](#prerequisites)
    * [The list of used commands in terminal](#the-list-of-used-commands-in-terminal)
    * [The whole terminal screen history in a file](#the-whole-terminal-screen-history-in-a-file)
    * [The result](#the-result)
  * [Linux](#linux)
    * [Prerequisites](#prerequisites-1)

## Laravel Homestead

Laravel's official development environment (vagrant/virtualbox)<br />

Useful urls:<br />
[Laravel Homestead](https://laravel.com/docs/5.4/homestead) official homepage<br />
[Laravel Homestead on GitHub](https://github.com/laravel/homestead)<br />
[laravel/homestead on Atlas](https://atlas.hashicorp.com/laravel/boxes/homestead): the official, pre-packaged Vagrant box<br />
[Laravel Settler](https://github.com/laravel/settler): The scripts that build the Laravel Homestead development environment.<br />

### macOS

#### Prerequisites

- [macOS Sierra](https://itunes.apple.com/hu/app/macos-sierra/id1127487414?mt=12) Version 10.12.3 (16D32)<br />
- [ORACLE VM VirtualBox Version 5.1.16 r113841](http://download.virtualbox.org/virtualbox/5.1.16/VirtualBox-5.1.16-113841-OSX.dmg) + [Extension Pack](http://download.virtualbox.org/virtualbox/5.1.16/Oracle_VM_VirtualBox_Extension_Pack-5.1.16-113841.vbox-extpack)<br />
- [Vagrant 1.9.2](https://releases.hashicorp.com/vagrant/1.9.2/vagrant_1.9.2.dmg)<br />

#### The list of used commands in terminal

- [laravel_vagrant_commands.txt](https://github.com/karolykass/laravel-devenv/blob/master/macOS/laravel_vagrant_commands.txt)

#### The whole terminal screen history in a file

- [laravel_vagrant_stdin_stdout.txt](https://github.com/karolykass/laravel-devenv/blob/master/macOS/laravel_vagrant_stdin_stdout.txt)

#### The result

[homestead.app](http://homestead.app)<br />
<br />
![alt text](https://github.com/karolykass/laravel-devenv/blob/master/macOS/laravel_homesteadapp_safari_screenshot.png "Laravel homestead.app Safari Screenshot")

### Linux

If you use Linux for your primary local development OS you have to do like this except for a few minor differences.

#### Prerequisites

- any Linux distribution, [Ubuntu Server 16.04.2 LTS](http://releases.ubuntu.com/16.04.2/ubuntu-16.04.2-server-amd64.iso) or [Debian 8.7.1](http://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-8.7.1-amd64-netinst.iso) suggested<br />
- ORACLE VM VirtualBox Version 5.1.16 r113841 [for Ubuntu 16.04 ("Xenial")](http://download.virtualbox.org/virtualbox/5.1.16/virtualbox-5.1_5.1.16-113841~Ubuntu~xenial_amd64.deb) or [for Debian 8 ("Jessie")](http://download.virtualbox.org/virtualbox/5.1.16/virtualbox-5.1_5.1.16-113841~Debian~jessie_amd64.deb) + [Extension Pack](http://download.virtualbox.org/virtualbox/5.1.16/Oracle_VM_VirtualBox_Extension_Pack-5.1.16-113841.vbox-extpack)<br />
- [Vagrant 1.9.2](https://releases.hashicorp.com/vagrant/1.9.2/vagrant_1.9.2_x86_64.deb)<br />

Best wishes!

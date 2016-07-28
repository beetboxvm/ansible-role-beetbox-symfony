# Ansible Role: Beetbox Symfony

[![Circle CI](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-symfony.svg?style=svg)](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-symfony)

An Ansible role that creates and installs a Symfony project on beetbox.

## Role Variables

Available variables are listed below, along with default values:

Symfony installer URL.

    symfony_installer_url: http://symfony.com/installer

Symfony installer bin path.

    symfony_bin_path: /usr/local/bin/symfony

Create new Symfony project.

    symfony_project_create: no

Symfony project name.

    symfony_project_name: my_project

Symfony project version.

    symfony_project_version: lts


# beetbox

https://github.com/beetboxvm/beetbox

## Requirements

* [Vagrant](https://www.vagrantup.com/) >= 1.8
* [Virtualbox](https://www.virtualbox.org/)
* [Vagrant Hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater)
* [Vagrant Auto-network](https://github.com/oscar-stack/vagrant-auto_network)

## Quickstart

  1. Open terminal (or [git bash](https://msysgit.github.io/) for windows users) and run the following commands --

  ```
  git clone https://github.com/beetboxvm/ansible-role-beetbox-symfony.git symfony && cd $_
  vagrant up
  ```

  2. Go to http://symfony.local/

  ```
  username: admin
  password: admin
  ```

## License

MIT
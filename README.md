# Ansible Role: autoarchive

[![Build Status](https://travis-ci.com/Bassinator/ansible-role-autoarchive.svg?branch=master)](https://travis-ci.com/Bassinator/ansible-role-autoarchive)

role to monitor a diretory and packup all changed file in archive subfolder

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    installation_os_user: vagrant
    www_dir: '/home/{{ installation_os_user }}/www/'

## Dependencies

None.


## Example Playbook


    - hosts: raspberries
      roles:
         - { role: bassinator.simplehttp, installation_os_user: pi }

## License

GNU GPLv3

## Author Information
his role was created in 2018 by [Bastian Bukatz](https://bassinator.github.io).

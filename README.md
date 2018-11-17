# Ansible Role: autoarchive

[![Build Status](https://travis-ci.com/Bassinator/ansible-role-autoarchive.svg?branch=master)](https://travis-ci.com/Bassinator/ansible-role-autoarchive)

archives all updated files with a given fileextension to an archive folder

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    installation_os_user: vagrant
    installation_os_group: vagrant
    fileextension: '.sb2'

## Dependencies

None.


## Example Playbook


    - hosts: all
      roles:
         - role: bassinator.autoarchive
           installation_os_user: <your_user>
           installation_os_group: <your_user_group>
           fileextension: '.xml'

## License

GNU GPLv3

## Author Information
This role was created in 2018 by [Bastian Bukatz](https://bassinator.github.io).

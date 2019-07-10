Tick Stack
=========

Ansible Role to install Tick Stack time series database on a
standalone Centos server.

## Requirements

## Role Variables
Variables for each application are broken down into different files
located under the group_vars file.


## Dependencies
 smtp and email tools like mailx are installed for alerting with tick-stack

## Example Playbook
 ansible-playbook -i tests/inventory roles/redis-sentinel-HA/main.yml

License
GNU GPLv3


Author Information
 Twitter: @TechGameTeddy

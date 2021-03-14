# Ansible-home
This is my home ansible setup. Feel free to suggest any improvements. :)

## apt.yml
This playbook is meant to be run periodically from Jenkins to update the system.

## jenkins.yml
This playbook deploys Jenkins on Docker with jenkins_home being mounted on external disk.

## plex.yml
This playbook deploys Plex server on Docker with configuration and library on external disk.

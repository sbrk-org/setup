# Setup for sbrk

## Pre-requisite

### Local workstation:

    ansible-galaxy collection install community.general

### Remove server

Have a user that can ssh, is in sudoers, and doesn't need a password.

Then run:

    pacman -S python

## Structure

- [playbooks](playbooks/) contains ansible playbooks to run,
- [roles](roles/) contains ansible roles,
- [group_vars](group_vars/) contains variables of the setup.

## Basic Usage

    ansible-playbook playbooks/all.yml

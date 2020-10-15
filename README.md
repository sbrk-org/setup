# Setup for sbrk

## Pre-requisite

    ansible-galaxy collection install community.general

## Structure

- [playbooks](playbooks/) contains ansible playbooks to run,
- [roles](roles/) contains ansible roles,
- [group_vars](group_vars/) contains variables of the setup.

## Basic Usage

    ansible-playbook playbooks/all.yml

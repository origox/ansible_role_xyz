# Ansible-role: ansible_git
[![CI](https://github.com/origox/ansible_role_XYZ/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/origox/ansible_role_XYZ/actions/workflows/ci.yml)

An Ansible role that install and configure XYZ for an user

## Requirements

None.

## Role Default Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    git_config:
      <section>:
        <key>: <value>

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - role: 
            src: https://github.com/origox/ansible_role_XYZ 

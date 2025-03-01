# Deployment
# Ansible Playbook for Automating Docker Installation and Configuration

## Overview

This playbook automates the installation of Docker on target servers and ensures that Docker is configured to start automatically on boot.

## Requirements

- **Ansible**: Make sure Ansible is installed on your local machine.
- **Target Servers**: The servers should be accessible via SSH and should be running Ubuntu or a compatible Linux distribution.

## Inventory File

Create an `hosts.ini` file to define the target servers. Here's an example:

```ini
[servers]
98.81.198.244 ansible_ssh_user=ubuntu




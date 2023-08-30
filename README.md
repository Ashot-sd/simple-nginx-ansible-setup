# NGINX Ansible Setup 🚀

An example of using Ansible to install and configure NGINX on your servers. Whether you're setting up a single server or scaling it up to multiple nodes, this guide will help you.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Quick Start](#quick-start)
- [Configuration](#configuration)

## Features

- 📦 Install the latest NGINX version.
- 🔧 Easily configurable using variables.
- 🔥 Built-in firewall management.

## Requirements

- Ansible 2.9 or newer.
- Target servers should run CentOS or RHEL.
- SSH access to your servers.

## Quick Start

1. Clone this repository:

   ```bash
   git clone https://github.com/Ashot-sd/simple-nginx-ansible-setup-example.git
    ```
    
1. Run the playbook:

   ```bash
   ansible-playbook -i inventories/hosts main.yml
    ```
    
### Configuration
All configurable variables are found in vars/main.yml. You can adjust settings like the NGINX version or specific firewall rules from there.
# centos-lamp-setup

This repository contains an Ansible playbook for automating the setup of a LAMP (Linux, Apache, MySQL, PHP) stack on CentOS servers.

## Introduction

The LAMP stack is a popular web development environment consisting of Linux as the operating system, Apache as the web server, MySQL as the database management system, and PHP as the server-side scripting language. This Ansible playbook streamlines the installation and configuration process, enabling you to quickly set up a LAMP environment on CentOS servers.

## Features

- Automated installation of Apache, MySQL, and PHP on CentOS servers.
- Configuration of Apache to serve web content.
- Configuration of MySQL for secure database operations.
- Easy customization of playbook variables to adapt to specific requirements.
- Repeatable and standardized deployment process for consistent results.

## Requirements

- CentOS server(s) with SSH access.
- Ansible installed on the control machine.

## Usage

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/bahy99/centos-lamp-setup.git

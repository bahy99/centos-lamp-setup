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
2. Modify the inventory.ini file to include the IP addresses or hostnames of your CentOS servers. Open the file and add the IP addresses or hostnames under the [centos_servers] group.
3. Adjust any desired variables in the lamp_playbook.yml file. Open the file and modify variables such as package versions, Apache configurations, MySQL settings, etc., according to your requirements.
4. Run the Ansible playbook:
   ansible-playbook -i inventory.ini lamp_playbook.yml
   This will execute the playbook and set up the LAMP stack on the specified CentOS servers.
5. After completion, you can access the web server by navigating to [http://"server-ip"] in your web browser.
# Customization
You can customize the playbook by modifying the following files:

- inventory.ini: Add or remove server IP addresses or hostnames to control which servers the playbook runs on.
- lamp_playbook.yml: Adjust variables, package versions, or configuration options to suit your requirements.
# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.   
 

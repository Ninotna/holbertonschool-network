# Networking Basics #1

## Project Overview

This project focuses on essential networking concepts related to localhost, IP addresses, and network interfaces. By completing this project, you will gain a deeper understanding of how network configurations work in a Linux environment, particularly Ubuntu, and how to manipulate and observe network settings and behaviors.

## Learning Objectives

By the end of this project, you will be able to:

- Explain what `localhost/127.0.0.1` is and why it is used.
- Understand the significance of `0.0.0.0` and how it is used in networking.
- Explain the purpose of the `/etc/hosts` file and how it affects domain name resolution.
- Display the active network interfaces on your machine.

## Requirements

- **General**:
  - Allowed editors: `vi`, `vim`, `emacs`.
  - All files will be interpreted on Ubuntu 20.04 LTS.
  - All files should end with a new line.
  - A `README.md` file is mandatory in the root of the project folder.
  - All Bash script files must be executable.
  - Scripts must pass `Shellcheck` (version 0.7.0 via `apt-get`) without errors.
  - The first line of all Bash scripts should be `#!/usr/bin/env bash`.
  - The second line of all Bash scripts should be a comment explaining what the script does.

## Tasks

| Task No | Task Name                   | Description                                                                                                                               | File Name                       | Points |
| ------- | --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | ------ |
| 0       | Change your home IP         | Write a Bash script to modify the `/etc/hosts` file so that `localhost` resolves to `127.0.0.2` and `facebook.com` resolves to `8.8.8.8`. | `0-change_your_home_IP`         | 2      |
| 1       | Show attached IPs           | Write a Bash script that displays all active IPv4 IP addresses on the machine.                                                            | `1-show_attached_IPs`           | 1      |
| 2       | Port listening on localhost | Write a Bash script that listens on port 98 on `localhost`.                                                                               | `2-port_listening_on_localhost` | 1      |

## Repository

- **GitHub repository**: `holbertonschool-network`
- **Directory**: `basics_1`

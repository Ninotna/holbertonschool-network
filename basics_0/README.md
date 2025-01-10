# Networking Basics #0

## Project Overview

This project covers the fundamental concepts of networking, focusing on understanding the OSI model, different types of networks, IP addressing, and key networking protocols such as TCP and UDP. By the end of this project, you will be able to explain these concepts clearly and apply them in practical scenarios.

## Learning Objectives

By completing this project, you will be able to:

- Explain the OSI model, its layers, and how it is organized.
- Differentiate between LAN, WAN, and the Internet.
- Understand IP addresses, including the differences between public and private addresses, and the importance of IPv6.
- Describe what localhost and subnets are.
- Compare TCP and UDP, and know the main differences between these protocols.
- Recognize important TCP/UDP port numbers, specifically for SSH, HTTP, and HTTPS.
- Use networking tools like `ping` and `netstat` to diagnose network connectivity.

## Requirements

- **General**:
  - Allowed editors: `vi`, `vim`, `emacs`.
  - All Bash script files will be interpreted on Ubuntu 20.04 LTS.
  - All files should end with a new line.
  - A `README.md` file is mandatory in the root of the project folder.
  - All Bash script files must be executable.
  - Scripts must pass `shellcheck` without errors.
  - The first line of all Bash scripts should be `#!/usr/bin/env bash`.
  - The second line of all Bash scripts should be a comment explaining what the script does.

## Tasks

| Task No | Task Name                  | Description                                                                                             | File Name                      | Points |
| ------- | -------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------ | ------ |
| 0       | OSI model                  | Explain the OSI model and its organization.                                                             | `0-OSI_model`                  | 2      |
| 1       | Types of network           | Differentiate between LAN, WAN, and Internet based on use case and geographical scope.                  | `1-types_of_network`           | 3      |
| 2       | MAC and IP address         | Explain the concepts of MAC and IP addresses and their roles in networking.                             | `2-MAC_and_IP_address`         | 2      |
| 3       | UDP and TCP                | Compare the characteristics and uses of TCP and UDP.                                                    | `3-UDP_and_TCP`                | 3      |
| 4       | TCP and UDP ports          | Write a Bash script to display listening TCP/UDP ports and their associated PIDs.                       | `4-TCP_and_UDP_ports`          | 1      |
| 5       | Is the host on the network | Write a Bash script to ping an IP address passed as an argument to check if the host is on the network. | `5-is_the_host_on_the_network` | 1      |

## Repository

- **GitHub repository**: `holbertonschool-network`
- **Directory**: `basics_0`

---

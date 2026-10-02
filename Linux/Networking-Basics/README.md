# Linux Networking Basics

## Overview

Today, I learned basic Linux networking commands using Kali Linux in VirtualBox. These commands help check IP addresses, test connectivity, inspect network interfaces, and troubleshoot network issues.

## Commands Practiced

| Command                      | Purpose                                      |
| ---------------------------- | -------------------------------------------- |
| `ip addr`                    | Displays network interfaces and IP addresses |
| `hostname -I`                | Displays assigned IP addresses               |
| `ping -c 4 google.com`       | Tests connectivity to a domain               |
| `nslookup google.com`        | Checks DNS name resolution                   |
| `ss -tuln`                   | Displays listening TCP and UDP sockets       |
| `ip route`                   | Displays the routing table                   |
| `curl -I https://google.com` | Checks an HTTP response using headers        |
| `ip link show`               | Displays network interfaces and their states |
| `ping -c 4 127.0.0.1`        | Tests local loopback connectivity            |

## Important Concepts

* **IP Address:** Identifies a device or network interface on a network.
* **DNS:** Resolves domain names to IP addresses.
* **Port:** Identifies a communication endpoint used by a service.
* **Gateway:** Provides a route to other networks.
* **Network Interface:** A virtual or physical interface used for network communication.
* **Loopback Address:** `127.0.0.1` refers to the local computer.

## Why Networking Matters in DevOps

Linux networking knowledge helps DevOps engineers troubleshoot connectivity problems, check application ports, investigate DNS issues, and verify whether web services respond.

## Practical Environment

* Operating System: Kali Linux
* Virtualization: Oracle VirtualBox
* Learning Approach: Hands-on terminal practice

## Learning Outcome

I practiced essential Linux networking commands and learned how they help inspect network configuration and troubleshoot connectivity.

**Linux Networking Basics — Completed!**

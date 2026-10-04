# Linux Package Management with APT

## Overview

I practiced Linux package management using APT in Kali Linux running inside Oracle VirtualBox. APT helps manage software packages, including searching, installing, inspecting, and maintaining package information.

## Commands Practiced

| Command | Purpose |
|---|---|
| `apt --version` | Displays the APT version |
| `apt search curl` | Searches for packages |
| `sudo apt update` | Refreshes available package information |
| `apt list --upgradable` | Lists packages with available upgrades |
| `sudo apt install tree` | Installs a package if needed |
| `tree --version` | Checks the installed version |
| `tree -L 2 ~` | Displays folders in a tree structure |
| `apt show tree` | Displays package information |
| `sudo apt clean` | Clears downloaded package files from the APT cache |
| `apt-config dump \| grep -i 'Cache'` | Filters APT configuration for cache-related settings |

## Important Concepts

- **APT:** A package-management tool used by Kali Linux and other Debian-based distributions.
- **Package repository:** A source containing software packages and package information.
- **Dependencies:** Other packages required by a software package.
- **Package cache:** A local location where downloaded package files may be stored.
- **Package upgrade:** Replaces an installed package version with a newer available version.

## Safety Practice

While examining package removal, APT proposed removing `tree` along with several Kali package groups. I cancelled the operation instead of confirming it.

This reinforced an important lesson: always review the complete list of proposed changes before confirming package operations.

## DevOps Relevance

Package management is important when preparing Linux servers, installing development tools, maintaining dependencies, and managing software updates.

## Learning Outcome

I gained hands-on experience with APT commands and learned to inspect package information and review proposed system changes before confirming them.

**Topic completed: Linux Package Management with APT.**

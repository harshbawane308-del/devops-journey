# Linux Services and Systemd

## Overview
I learned how Linux services work and practiced inspecting services and system logs using Kali Linux in Oracle VirtualBox.

## What Is systemd?
`systemd` is a system and service manager used by many Linux distributions. It manages services and other system components.

A service is a program that runs in the background to provide a specific function.

## Commands Practiced

| Command | Purpose |
|---|---|
| `ps -p 1 -o comm=` | Checks the name of process ID 1 |
| `systemctl status cron` | Displays detailed status of the cron service |
| `systemctl list-units --type=service --state=running` | Lists currently running services |
| `systemctl is-enabled cron` | Checks whether cron is configured to start automatically |
| `systemctl is-active cron` | Checks whether cron is currently active |
| `journalctl -u cron -n 10 --no-pager` | Displays recent cron service logs |
| `journalctl -u cron -p err --no-pager` | Filters cron logs for error-priority entries |
| `journalctl -n 15 --no-pager` | Displays recent system-wide logs |

## Important Concepts

- **Active:** Indicates that a service is currently active.
- **Enabled:** Indicates that a service is configured to start automatically at boot.
- **PID:** Process ID used to identify a running process.
- **Journal:** The systemd logging system used to collect and inspect system logs.
- **Cron:** A service used to run scheduled tasks.

## Practical Observations

- Confirmed that `systemd` was running as process ID 1.
- Checked that the `cron` service was active and enabled.
- Listed running services on Kali Linux.
- Inspected cron logs and system-wide logs.
- Observed that no error-priority entries were returned for the cron service by the error-filtered query.
- Learned to review command syntax carefully before running service-management operations.

## DevOps Relevance

Service management and log inspection are important for Linux server administration, application troubleshooting, and maintaining reliable services in DevOps environments.

## Learning Outcome

I gained hands-on experience inspecting Linux services, checking their status, understanding startup configuration, and investigating system logs.

**Topic: Linux Services and Systemd — Completed.**

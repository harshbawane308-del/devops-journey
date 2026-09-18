# Day 5 – Linux Process Management

## What I Learned

Today I learned about Linux processes and how to monitor and manage running programs.

A process is a running instance of a program. Every process has a unique Process ID (PID).

## Commands Learned

| Command | Purpose |
|---|---|
| `ps` | Shows currently running processes |
| `ps aux` | Shows detailed information about running processes |
| `top` | Monitors processes in real time |
| `htop` | Provides an interactive process monitoring view |
| `pgrep` | Finds the PID of a process |
| `kill` | Stops a running process |
| `jobs` | Shows background jobs |
| `fg` | Brings a background job to the foreground |
| `&` | Runs a command in the background |

## Practical Work

I practiced viewing and managing Linux processes using the terminal.

I created a test background process:

```bash
sleep 300 & 
```
DevOps Use Case

Process management is important when working with Linux servers.

DevOps engineers may need to monitor applications, identify resource-consuming processes, troubleshoot running services, and stop processes that are causing problems.

Commands such as ps, top, htop, pgrep, and kill are useful for these tasks.

Important Learning

Today I learned that Linux processes can be monitored and managed using the command line.

I also learned how to find a process using its PID and safely stop a test process.

Learning Outcome

Today I gained practical experience with Linux process management and learned how to monitor, find, and manage running processes.

# Day 4 – Linux File Permissions & Ownership

## What I Learned

Today I learned how Linux controls access to files and directories using permissions and ownership.

Linux permissions are given to three types of users:

- Owner
- Group
- Others

The three basic permissions are:

- `r` – Read
- `w` – Write
- `x` – Execute

## Commands Learned

| Command | Purpose |
|---|---|
| `ls -l` | Shows detailed file information and permissions |
| `chmod` | Changes file permissions |
| `chown` | Changes file owner |
| `chgrp` | Changes file group |

## Permission Values

| Permission | Value |
|---|---:|
| `r` | 4 |
| `w` | 2 |
| `x` | 1 |

Common permission combinations:

```text
644 = rw-r--r--
755 = rwxr-xr-x
600 = rw-------

## Learning Outcome

Today I learned how Linux file permissions work and practiced changing permissions using `chmod`.

I also learned the basic concepts of file ownership and groups.

**Day 4 Completed ✅**

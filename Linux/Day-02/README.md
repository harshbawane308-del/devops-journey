# Day 2 – Linux File and Directory Management

## Commands Learned

| Command | Purpose |
|---|---|
| `cd` | Change directory |
| `mkdir` | Create a directory |
| `touch` | Create an empty file |
| `cat` | Display file contents |
| `echo` | Display or write text |
| `cp` | Copy files or directories |
| `mv` | Move or rename files |
| `rm` | Remove files |
| `rmdir` | Remove empty directories |

## Special Paths

| Symbol | Meaning |
|---|---|
| `/` | Root directory |
| `~` | Current user's home directory |
| `.` | Current directory |
| `..` | Parent directory |
| `-` | Previous directory with `cd -` |

## Redirection

### `>`

Writes content to a file and replaces existing content.

```bash
echo "Hello" > file.txt

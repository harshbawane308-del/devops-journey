# Day 3 – Viewing, Searching & Finding Files

## Commands Learned

| Command | Purpose |
|---|---|
| `head` | Shows the beginning of a file |
| `tail` | Shows the end of a file |
| `less` | Views a file page by page |
| `more` | Views a file page by page |
| `grep` | Searches for text inside files |
| `find` | Finds files and directories |
| `which` | Shows the location of a command |
| `history` | Shows previously executed commands |
| `man` | Displays the manual/documentation for a command |
| `wc` | Counts lines, words, and characters |

## Important Options

```bash
head -n 5 file.txt
tail -n 5 file.txt
tail -f application.log
grep -i "error" application.log
grep -n "ERROR" application.log
grep -r "error" .
find . -name "*.txt"
find . -type f
wc -l application.log

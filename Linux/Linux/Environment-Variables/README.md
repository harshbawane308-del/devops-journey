# Linux Environment Variables

## Overview

Today I learned about environment variables in Linux using Kali Linux. Environment variables store configuration values that are available to the shell and applications.

## Commands Practiced

| Command | Purpose |
|---|---|
| `printenv` | Displays environment variables |
| `echo $HOME` | Displays the home directory |
| `echo $USER` | Displays the current username |
| `echo $PATH` | Displays the command search path |
| `which ls` | Checks how a command is resolved |
| `command -v ls` | Checks command resolution |
| `type -a ls` | Shows aliases and executable locations |
| `export PROJECT="DevOps"` | Creates an environment variable |
| `printenv \| grep PROJECT` | Searches for a specific variable |
| `bash -c 'echo $PROJECT'` | Tests an exported variable in a child process |
| `unset PROJECT` | Removes a temporary variable |
| `printenv PATH` | Displays the PATH environment variable |
| `ls -a ~` | Views hidden files in the home directory |
| `ls -l ~/.zshrc` | Checks the Zsh configuration file |
| `cat ~/.zshrc` | Reads the Zsh configuration |
| `source ~/.zshrc` | Reloads the Zsh configuration |
| `zsh -c 'echo $DEVOPS_LEARNER'` | Verifies a variable in a new Zsh session |

## Important Environment Variables

### HOME
```bash
echo $HOME
```

Shows the user's home directory.

### USER
```bash
echo $USER
```

Shows the current username.

### PATH
```bash
echo $PATH
```

Contains directories where Linux searches for executable commands.

## Temporary Environment Variable

I created a temporary variable:

```bash
export PROJECT="DevOps"
```

Then verified it with:

```bash
echo $PROJECT
```

I also tested that exported variables are available to child processes.

## Permanent Environment Variable

I added the following variable to my Zsh configuration:

```bash
export DEVOPS_LEARNER="Linux"
```

After reloading `.zshrc`, I verified it using a new Zsh shell.

## DevOps Relevance

Environment variables are widely used in DevOps for application configuration, deployment settings, paths, API configuration, and other runtime values.

They are especially useful because configuration can be separated from application code.

## Important Security Note

Sensitive information such as passwords, API keys, and access tokens should not be hard-coded into scripts or publicly committed to GitHub.

## Learning Outcome

I gained practical experience with Linux environment variables, `PATH`, shell configuration, temporary variables, exported variables, and persistent environment variables using Zsh.

**Linux Environment Variables — Completed ✅**

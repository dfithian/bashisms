# bashisms

Annotated commands and utilities, persisted to help me remember them.

# commands

```bash
top # then press "1" to get CPU% per core

ps faxwu # subprocess tree, add more w's for more info
ps axl

lsof -p <pid> # list open files, look for pipes

strace -p <pid> # look at the syscalls for this process
strace -f <command> # follow a command - everything and everything it forks

free -h # human readable
```

# nix

```bash
nix-shell <command> --option fallback true --option substitute false # if hydra is down
```

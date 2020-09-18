# List of useful commands

## Git

### Ammend last commit
```zsh
git commit --amend
```

## Terminal

### Kill process running on port `1234`

```zsh
sudo lsof -i tcp:1234
# Returns👇 where PID is the ID of our process
# COMMAND  PID USER   FD   TYPE             DEVICE SIZE/OFF NODE NAME
# node    5261 miro   23u  IPv4 0x15e7fe15968959d9      0t0  TCP *:http-alt (LISTEN)

# Next we kill the process with that ID
kill -9 5261

```

## Vim
* Save file: `:w`
* Quit: `:q`
# AntiGravity Quota Top

Based on https://github.com/cornfields/LevityCheck

With changes to:
- run on MacOs
- Run in a curses terminal app that shows results like top/htop

## Set up
add `ag_top` to your path, or add/symlink it to your /usr/bin

### Using `install.sh`
`install.sh` will symlink ag_top to `~/.local/bin/`, after which you can run it with `ag_top` or `ag_top -l [refresh]` or `ag_top -p/--print`

## Run with
### default, 60 second refresh
```sh
ag_top
```

### user-provided refresh
```sh
ag_top -l [<seconds to refresh>]
```

### Print and exit
```sh
ag_top -p/--print
```


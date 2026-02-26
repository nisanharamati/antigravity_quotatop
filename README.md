# AntiGravity Quota Top

Based on https://github.com/cornfields/LevityCheck

With changes to:
- run on MacOs
- Run in a curses terminal app that shows results like top/htop

## Set up
add `ag_quotatop` to your path, or add/symlink it to your /usr/bin

### Using `install.sh`
`install.sh` will symlink ag_quotatop to ag_top in `~/.local/bin/`, after which you can run it with `ag_top` or `ag_top -l [refresh]`

## Run with
```sh
ag_quotatop -l [<seconds to refresh>]
```

Default refresh is 60 seconds

To run the original levitycheck print-and-exit, use `ag_quotatop` with no args


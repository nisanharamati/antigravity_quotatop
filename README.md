# AntiGravity Quota Top

Based on https://github.com/cornfields/LevityCheck

With changes to:
- run on MacOs
- Run in a curses terminal app that shows results like top/htop

## Set up
add `ag_quotatop` to your path, or add/symlink it to your /usr/bin

## Run with
```sh
ag_quotatop -l [<seconds to refresh>]
```

Default refresh is 60 seconds

To run the original levitycheck print-and-exit, use `ag_quotatop` with no args


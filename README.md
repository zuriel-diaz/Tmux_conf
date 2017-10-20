[Tmux](http:////tmux.sourceforge.net/) is a terminal multiplexer.

- Tested with tmux 1.5+.
- Prefix mapped to Ctrl-A for `screen` users.

## Steps

1. Download:

``` bash 
git clone --recursive https://github.com/xthr3mx/Tmux_conf.git ~/.tmux
```

2. Generate simlynk from tmux config folder.

``` bash
ln -s ~/.tmux/tmux.conf ~/.tmux.conf
```
## Start tmux 

1. Update config:

``` bash
tmux source-file ~/.tmux.conf
```

2. Start:

``` bash
tmux new -s session-name
```
And press `Control + a` then `d` to go back to the terminal.

To rettach a previous session: 

``` bash
tmux attach -t session-name
```
To reload config file (inside tmux session)

``` bash
<Control + a>: (which could Ctrl-q or Ctrl-f if you overidden it) then source-file ~/.tmux.conf
```

Done!
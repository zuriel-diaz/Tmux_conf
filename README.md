Tmux is a terminal multiplexer. Tested with tmux 1.5 and 1.6.

1.Download:

git clone https://github.com/xthr3mx/Tmux_conf.git ~/tmux

2.Copy tmux config to home

ln -s ~/tmux/tmux.conf ~/.tmux.conf

Enjoy!

Start tmux

To start a session:

tmux

To reattach a previous session:

tmux attach

To reload config file

<Control + b>: (which could Ctrl-B or Ctrl-A if you overidden it) then source-file ~/.tmux.conf



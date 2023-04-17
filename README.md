# devconf
A must-have configuration of development tools for efficient command-line work on Linux systems.

## Install tmux.conf

Copy the follow script and run it in your terminal
```bash
git clone git@github.com:tmux-plugins/tpm.git ~/.tmux/plugins/tpm && \
git@github.com:yahaa/devconf.git /tmp/devconf && \
cp /tmp/devconf/.tmux.conf ~/.tmux.conf && \
tmux source ~/.tmux.conf
```

Press prefix + I (capital i, as in Install) to fetch the plugin.


## Install alacritty.yml

Copy the follow script and run it in your terminal
```bash
git@github.com:yahaa/devconf.git /tmp/devconf && \
cp /tmp/devconf/alacritty.yml ~/.config/alacritty/alacritty.yml 
```


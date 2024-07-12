#### How to quickly add tmux config


```bash
mkdir ~/.config/tmux/
```

```bash
wget https://raw.githubusercontent.com/robnmrz/dotfiles/master/tmux/tmux.conf ~/.config/tmux/
```

After that start restart tmux or source the config file

```bash
nvim ~/.config/tmux/tmux.conf
```
After this hit <leader> + I to install the plugins. Restart again and voilà

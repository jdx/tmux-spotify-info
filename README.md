tmux-spotify-info
=================

Shows current song playing on spotify in your tmux statusline. OSX only.

Installation
============

Put `tmux-spotify-info` in your path. I suggest `~/bin`.

Add the following to `~/.tmux.conf`

```
set -g status-right '#(tmux-spotify-info)'
```

Or for a more complete statusline like [the one I have](https://github.com/dickeyxxx/dotfiles/blob/master/home/.tmux.conf)

Also check out [tmux-cpu-info](https://github.com/dickeyxxx/tmux-cpu-info)

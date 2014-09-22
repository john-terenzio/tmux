JT's tmux Config
================

This is my tmux configuration. It works on Linux and OS X and uses a custom
Solarized Dark color scheme. The goal is to make tmux behave more like Vim. If
you are running on an OS X laptop, it can also take advantage of a command
called `battery` that prints the percentage of battery remaining and put that
in the status bar. `battery` is included in the `bin/` directory.

The default location for the tmux configuation file is `~/.tmux.conf` but I
prefer keeping everything in a folder at `~/.tmux/`. To install this, rename
the `conf/` directory to `~/.tmux/` and add
`alias tmux='tmux -f ~/.tmux/tmux.conf'` to your `.bashrc` (or equivalent).

![screen shot 2014-09-21 at 9 03 29 pm](https://cloud.githubusercontent.com/assets/445973/4351517/747ba51c-420d-11e4-8586-35437c41515a.png)

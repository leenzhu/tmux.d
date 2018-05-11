# tmux.d
This is my tmux config

# Usage

```sh
git clone https://github.com/leenzhu/tmux.d.git ~/.tmux.d
ln -s ~/.tmux.d/tmux.conf ~/.tmux.conf
```

# Plugin
## better-mouse

```sh

```

1. Clone the repo:

    cd ~/.tmux.d
    git clone https://github.com/nhdaly/tmux-better-mouse-mode better-mouse

1. Add this line to the bottom of `.tmux.conf`:

        run-shell ~/.tmux.d/better-mouse/scroll_copy_mode.tmux

1. Reload TMUX environment:

        # type this in terminal
        $ tmux source-file ~/.tmux.conf


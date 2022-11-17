# Dev essentials

Inspired (and mostly copied) from [mresvanis' dotfiles](https://github.com/mresvanis/dotfiles/).

The simple `setup` script below needs the following software.

* [git](https://git-scm.com/)
* [vim](https://github.com/vim/vim)
* [tmux](https://github.com/tmux/tmux)
* [tig](https://github.com/jonas/tig)
* [fzf](https://github.com/junegunn/fzf)
* [zsh](https://ohmyz.sh)

## Setup

Clone the repo:

```bash
git clone git@github.com:xenosdio/dotfiles.git ~/.dotfiles
```

Link the respective rcs and dirs to your home by running the `setup` script:

```bash
cd ~/.dotfiles && ./setup
```

## tmux

Set the tmux plugin manager:

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

After opening tmux install the plugins referenced in `.tmux.config` with:

```bash
Ctrl-a I
```

## iterm2 color scheme

Via iTerm preferences:

* Launch iTerm 2
* Click on iTerm2 menu title
* Select Preferences... option
* Select Profiles
* Navigate to Colors tab
* Click on Color Presets
* Click on Import
* Select the [iterm2/gruvbox.itermcolors](iterm2/gruvbox.itermcolors) file
* Click on Color Presets and choose a color scheme

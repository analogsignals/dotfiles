# Jeeven's dotfiles
**Caveat emptor!** These dotfiles mostly contain what may seem like insane defaults, and settings that may leave you scratching your head.

Probably includes dotfiles for things like neovim, zsh, brewfiles, and whatever trendy tool that's in vogue whenver you read this.

You may notice there is no tmux.conf. Yes.

I like to live *dangerously*

#Install
This installs chezmoi and sets up the dotfiles in a snazzy little oneliner:
```console
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME
```

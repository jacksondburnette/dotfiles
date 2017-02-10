# Generic Dotfiles

### Why?

This repository houses configuration dotfiles in a way that makes them easily
transferable between systems. I created it because, as I researched the existing
dotfile repositories on github, they all seemed a bit heavy weight.

### What?

The dotfiles repository should be cloned into the $HOME directory of your machine
and should serve as the location for all dotfiles that belong in the $HOME directory.

### How?

Simply place any given configuration file in the dotfiles directory with the format
'basename.symlink', run 'bash dotfiles/bootstrap' and a symlink '.basename' will be
created.


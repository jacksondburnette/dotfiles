# Generic Dotfiles

## Why?

This repository houses configuration dotfiles in a way that makes them easily
transferable between systems. I created it because, as I researched the existing
dotfile repositories on github, they all seemed a bit heavy weight.

## What?

The dotfiles repository should be cloned into the $HOME directory of your machine
and should serve as the location for all dotfiles that belong in the $HOME directory.

## How?

In the dotfiles directory, create your configuration files and specify that they 
they should be symlinked --> basename.symlink results in .basname in the home directory
when `bootstrap` is run.

For example,
```bash
$ git clone https://github.com/jacksondburnette/dotfiles.git dotfiles
$ cd dotfiles
$ touch bashrc.symlink
$ bash bootstrap
```
bashrc.symlink results in a .bashrc in the $HOME directory.

## Thanks

This project was inspired by @holman [dotfile] (https://github.com/holman/dotfiles). Specifically,
`bootstrap` (with some manipulation) was taken directly from that project.


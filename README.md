# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
sudo apt install git
```

### Stow

```
sudo apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
git clone --recursive git@github.com:Marstar03/dotfiles.git ~/dotfiles
cd ~/dotfiles
```

Then use GNU stow to create symlinks

```
stow .
```

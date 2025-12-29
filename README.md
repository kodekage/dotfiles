# dotfiles

This repo contains default dotfile configurations i use accross machines and will grow from time to time as my career advances.

#### Prerequisite

`Homebrew`, `Stow` and `Git` needs to be installed before cloning the repo

Homebre install
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Stow and Git install
```bash
brew install stow git
```

#### Installation and Setup

Navigitate to system home directory and run the following commands

```
git clone git@github.com:kodekage/dotfiles.git

cd dotfiles

stow git tmux
```

Congratulations future @kodekage, your dotfiles has been setup on your new machine!




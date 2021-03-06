+++
title = "Install Linux"
date = 2019-11-27
updated =2020-03-07
+++

# Update

```bash
sudo pacman -Syu 
```

# Install

```bash
sudo apt install zsh tilix build-essential htop keepassx python3-venv python3-pip python-dev python3-dev libevent-dev npm fonts-powerline 
sudo apt install openjdk-11-jre openjdk-11-jdk docker.io docker-compose yarn flameshot
sudo apt install texlive-full texmaker
```

## Brew

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install.sh)"
test -r ~/.zshrc && echo "eval \$($(brew --prefix)/bin/brew shellenv)" >>~/.zshrc
```

# Brew with shortcuts

```bash
brew install fzf
$(brew --prefix)/opt/fzf/install
```

# Snap

```bash
sudo apt install snapd
snap xbindkey -y
sudo snap install code --classic
sudo snap install pycharm-community --classic
sudo snap install intellij-community --classic
```

# ohmyzsh

Also makes **zsh default terminal**

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

# Git config / dotfiles repository

As explained [here](https://www.atlassian.com/git/tutorials/dotfiles) or in the pdf in negasave backup folder. The following is not yet 100% tested, but should work. 

1. copy `.zshrc` from [dotfiles](https://github.com/medizinmensch/dotfiles/) repository to `~` path
2. exec
```bash
echo ".cfg" >> .gitignore
git clone --bare https://github.com/medizinmensch/dotfiles/ $Home/.dotfiles
config checkout
config config --local status.showUntrackedFiles no
```

(to prevent recursion problems, clone, download and ignore untracked files)

# i3
To change i3 color config, copy the file from `website/backups/.i3/config` to `~/.i3/config`. Changed is:

* Theme Colors -> class -> client.focues / background

# Duplicati
Like explained [here](https://xo.tc/installing-duplicati-on-an-arch-linux-laptop.html). 

**Install:**

```bash
git clone https://aur.archlinux.org/duplicati-latest.git
cd duplicati-latest
makepkg -si
```

**Start service:**

```bash
sudo systemctl enable duplicati.service
sudo systemctl start duplicati.service
```
Access at [localhost:8200](http://localhost:8200)

# TODO

- make terminator default terminal
- configs ?

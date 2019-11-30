# Update

```bash sudo apt update udo apt upgrade ```

# Install

```bash
sudo apt install zsh tilix build-essential htop keepassx python3-venv python3-pip python-dev python3-dev libevent-dev npm fonts-powerline 
sudo apt install openjdk-11-jre openjdk-11-jdk docker.io docker-compose yarn
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

# i3 config
To change i3 color config, copy the file from `website/backups/.i3/config` to `~/.i3/config`. Changed is:

* Theme Colors -> class -> client.focues / background


# TODO

- make terminator default terminal
- configs ?


# Execute all

```bash





```



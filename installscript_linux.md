# Update

>sudo apt update
>sudo apt upgrade

# Install
```bash
sudo apt install zsh tilix build-essential htop keepassx python3-venv python3-pip python-dev python3-dev libevent-dev npm
sudo apt install openjdk-11-jre openjdk-11-jdk

wget https://github.com/sharkdp/bat/releases/download/v0.10.0/bat_0.10.0_amd64.deb
sudo dpkg -i bat_0.10.0_amd64.deb
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

sudo apt install snapd
snap xbindkey -y
sudo snap install --classic code
sudo snap install pycharm-community --classic
```

# Setup

## make zsh default shell

>sudo chsh -s /bin/zsh

## make tilix default terminal
>gsettings set org.cinnamon.desktop.default-applications.terminal exec 'terminator'

# TODO
fsearch 
configs ?

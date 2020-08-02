# dotfiles

This repository contains some configurations and applications for local development.

## zsh

### Configuration files

- .zshrc: current configuration.
- powerleve9k.zshrc: old configuration.

### Theme

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```
Set ZSH_THEME="powerlevel10k/powerlevel10k" in ~/.zshrc.

### Plugins

<https://github.com/zsh-users/zsh-syntax-highlighting>

<https://github.com/zsh-users/zsh-autosuggestions>

## Homebrew

```bash
brew cask install visual-studio-code
brew cask install postman
brew cask install the-unarchiver
brew cask install spotify
brew cask install transmission
brew cask install google-chrome
brew cask install discord
brew cask install vlc
brew cask install whatsapp
brew cask install docker
brew install nmap
brew install htop
```

## NodeJS

```bash
brew install nvm
nvm install node
brew install yarn
```
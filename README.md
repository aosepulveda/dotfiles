# dotfiles

This repository contains some configurations and applications for local development.

## zsh

### Theme

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```
Set ZSH_THEME="powerlevel10k/powerlevel10k" in ~/.zshrc.

### Fonts
Nerd Fonts

<https://github.com/ryanoasis/nerd-fonts>

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
brew cask install vlc
```

## NodeJS

```bash
brew install nvm
nvm install node
brew install yarn
```
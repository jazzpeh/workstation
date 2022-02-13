# Terminal

## Homebrew

Install [homebre](https://brew.sh/)w if not already.

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## iTerm2

Install [iTerm2](https://iterm2.com/).

```sh
# via brew
brew cask install iterm2
```

## Oh My Zsh

Install [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh).

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

> Install zsh if not already `brew install zsh`

## Customisation

Customise terminal with the follow:

```sh
# create file it not already exists
vim ~/.zshrc

# Path to your oh-my-zsh installation.
export ZSH="/Users/jazzpeh/.oh-my-zsh"

# Set theme
ZSH_THEME=cobalt2

# Set plugins
plugins=(
  git
  zsh-autosuggestions
  last-working-dir
  web-search
  extract
  history
)

# Source default oh-my-zsh script
source $ZSH/oh-my-zsh.sh

# Source zsh syntax zsh-syntax-highlighting plugin
source /Users/jazzpeh/.oh-my-zsh/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```
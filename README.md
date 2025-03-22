## dotfiles 

Managed by [chezmoi](https://www.chezmoi.io/).

### Installation

```sh
chezmoi init --apply jkyochen
```

> Install chezmoi and apply dotfiles

```sh
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply jkyochen
```

### iTerm2

```sh
# Specify the preferences directory
defaults write com.googlecode.iterm2 PrefsCustomFolder -string "~/.config/iterm2"

# Tell iTerm2 to use the custom preferences in the directory
defaults write com.googlecode.iterm2 LoadPrefsFromCustomFolder -bool true
```

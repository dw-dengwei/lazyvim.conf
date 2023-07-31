# 💤 LazyVim Config

Fork https://github.com/LazyVim/starter.

# Requirements
- npm
- gcc
- fdfind
- [optinal] node v16 for grammarly-langageserver

# Installation
- Make a backup of your current Neovim files:
``` bash
# required
mv ~/.config/nvim ~/.config/nvim.bak

# optional but recommended
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```
- Clone this repo
```bash
git clone https://github.com/dw-dengwei/lazyvim.conf.git ~/.config/nvim
```
- Remove the `.git` folder, so you can add it to your own repo later
```bash
rm -rf ~/.config/nvim/.git
```
- Start Neovim!
```bash
nvim
```

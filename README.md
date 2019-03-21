# flatpak-zsh-completion
Flatpak completion for Z shell (Zsh)

![GitHub](https://img.shields.io/github/license/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge) ![GitHub last commit](https://img.shields.io/github/last-commit/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge) ![GitHub stars](https://img.shields.io/github/stars/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge)

![flatpak-zsh](https://user-images.githubusercontent.com/15098724/50722513-41ac0c80-1085-11e9-850e-85cff36f5b1c.gif)

# Dependencies
- `zsh`

# Compatible Z shell plugin frameworks
- [`antibody`](https://getantibody.github.io/)
- [`antigen`](https://antigen.sharats.me/)
- [`oh-my-zsh`](https://ohmyz.sh/)
- [`zgen`](https://github.com/tarjoilija/zgen)
- [`zplug`](https://zplug.sh/)

# Installation
### Using Antibody:
- If you use a separate plugins file
```bash
echo "antibody github bilelmoussaoui/flatpak-zsh-completion" >> ${ZDOTDIR:-$HOME}/.zsh_plugins.txt
```
- If you list your plugins within `.zshrc`
```bash
echo "antibody github bilelmoussaoui/flatpak-zsh-completion" >> ${ZDOTDIR:-$HOME}/.zshrc
```
### Using Antigen:
```bash
echo "antigen bundle bilelmoussaoui/flatpak-zsh-completion" >> ${ZDOTDIR:-$HOME}/.zshrc
```
### Using Oh-My-Zsh:
1. Clone this repository under the custom plugins directory
```bash
cd $ZSH_CUSTOM/plugins
git clone https://github.com/bilelmoussaoui/flatpak-zsh-completion flatpak
```
2. Add `flatpak` to the plugins array in `.zshrc`
```bash
plugins+=(flatpak)
```
### Using Zgen:
- Place the following string on its own line after `source "${HOME}/.zgen/zgen.zsh"` in `.zshrc`
```bash
zgen load bilelmoussaoui/flatpak-zsh-completion
```
### Using ZPlug: 
Add this string on its own line between `source ~/.zplug/init.zsh` and `zplug load` in `.zshrc`
```bash
zplug "bilelmoussaoui/flatpak-zsh-completion", nice:10
```

# Usage
To start using:
- Restart your terminal emulator

  or

- Source the `.zshrc` file
```bash
source ${ZDOTDIR:-$HOME}/.zshrc
```

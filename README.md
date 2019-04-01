# Flatpak completion for Z shell (Zsh)

<p align="center">
  <img src="https://user-images.githubusercontent.com/15098724/55282117-f8253380-52fa-11e9-95a3-ccae83b23034.png" alt="Flatpak logo" />
  <img src="https://user-images.githubusercontent.com/15098724/55282119-02dfc880-52fb-11e9-90b3-6c2c43ad5883.png" alt="Zsh wizard logo" />
</p>

<p align="center">
    <a href="https://github.com/bilelmoussaoui/flatpak-zsh-completion/stargazers" alt="GitHub stars received">
        <img src="https://img.shields.io/github/stars/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge" /></a>
    <a href="https://github.com/bilelmoussaoui/flatpak-zsh-completion/graphs/contributors" alt="GitHub contributors">
        <img src="https://img.shields.io/github/contributors/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge" /></a>
    <a href="https://app.codacy.com/project/bilelmoussaoui/flatpak-zsh-completion/dashboard" alt="Codacy quality assessment">
        <img src="https://img.shields.io/codacy/grade/c14f0b6261094edc8586ebdb6c83deab.svg?style=for-the-badge" /></a>
    <a href="https://github.com/bilelmoussaoui/flatpak-zsh-completion/issues" alt="GitHub issues">
        <img src="https://img.shields.io/github/issues-raw/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge" /></a>
    <img src="https://img.shields.io/github/languages/code-size/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge"
        alt="Repository code size in bytes">
    <a href="https://github.com/bilelmoussaoui/flatpak-zsh-completion/commits/master" alt="GitHub last commit">
        <img src="https://img.shields.io/github/last-commit/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge" /></a>
    <a href="https://github.com/bilelmoussaoui/flatpak-zsh-completion/blob/master/LICENSE" alt="Repository licensed under">
        <img src="https://img.shields.io/github/license/bilelmoussaoui/flatpak-zsh-completion.svg?style=for-the-badge" /></a>
</p>

<p align="center">
    <img src="https://user-images.githubusercontent.com/15098724/50722513-41ac0c80-1085-11e9-850e-85cff36f5b1c.gif"
        alt="GIF animation of command completion occuring in a Z shell terminal" />
</p>

## Dependencies

- [zsh](http://zsh.sourceforge.net/)

## Compatible Z shell plugin frameworks

- [antibody](https://getantibody.github.io/)
- [antigen](https://antigen.sharats.me/)
- [oh-my-zsh](https://ohmyz.sh/)
- [zgen](https://github.com/tarjoilija/zgen)
- [zplug](https://zplug.sh/)

## Installation

### Using Antibody

- If you use a separate plugins file

```bash
echo "antibody github bilelmoussaoui/flatpak-zsh-completion" >> ${ZDOTDIR:-$HOME}/.zsh_plugins.txt
```

- If you list your plugins within `.zshrc`

```bash
echo "antibody github bilelmoussaoui/flatpak-zsh-completion" >> ${ZDOTDIR:-$HOME}/.zshrc
```

### Using Antigen

```bash
echo "antigen bundle bilelmoussaoui/flatpak-zsh-completion" >> ${ZDOTDIR:-$HOME}/.zshrc
```

### Using Oh-My-Zsh

1. Clone this repository under the custom plugins directory

```bash
cd $ZSH_CUSTOM/plugins
git clone https://github.com/bilelmoussaoui/flatpak-zsh-completion flatpak
```

1. Add `flatpak` to the plugins array in `.zshrc`

```bash
plugins+=(flatpak)
```

### Using Zgen

- Place the following string on its own line  in `.zshrc` directly after `source "${HOME}/.zgen/zgen.zsh"`

```bash
zgen load bilelmoussaoui/flatpak-zsh-completion
```

### Using ZPlug

Add this string on its own line in `.zshrc` between `source ~/.zplug/init.zsh` and `zplug load`

```bash
zplug "bilelmoussaoui/flatpak-zsh-completion", nice:10
```

## Getting started

Choose one of the methods below to activate the plugin on your system:

- Restart your terminal emulator

  or

- Source the `.zshrc` file

```bash
source ${ZDOTDIR:-$HOME}/.zshrc
```

## Donating

<p><img src="https://img.shields.io/static/v1.svg?label=PayPal&logo=paypal&logoWidth=30&labelColor=grey&color=success&message=Donate%20Here&style=popout-square&link=https://www.paypal.me/BilalELMoussaoui" /></p>

## License

This code is provided under the terms of the GNU General Public License, version 3.0. The full text describing the rights and responsibilities of those who make use of it, can be found in the [LICENSE](https://github.com/bilelmoussaoui/flatpak-zsh-completion/blob/master/LICENSE) file.

SPDX­-License­-Identifier: GPL-3.0-only

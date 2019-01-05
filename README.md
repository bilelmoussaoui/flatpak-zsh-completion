# flatpak-zsh-completion
Flatpak completion for ZSH

![flatpak-zsh](https://user-images.githubusercontent.com/15098724/50722513-41ac0c80-1085-11e9-850e-85cff36f5b1c.gif)

# Dependencies
- `zsh`
- `oh-my-zsh`

# Installation
### Using Antigen :
Bundle `flatpak-zsh-completion` in your `.zshrc`
```bash
  antigen bundle bil-elmoussaoui/flatpak-zsh-completion
```
### Using ZPlug : 
Load `flatpak-zsh-completion` as a plugin in your `.zshrc`
```bash
  zplug "bil-elmoussaoui/flatpak-zsh-completion", nice:10
```
### Using Oh-my-ZSH :
Clone this repository under the custom plugins directory
```bash
  cd $ZSH_CUSTOM
  git clone https://github.com/bil-elmoussaoui/flatpak-zsh-completion flatpak
```

Load the plugin on `.zshrc`
```bash
  plugins+=(flatpak)
```

Restart your terminal emulator or source the `.zshrc` file
```bash
source ~/.zshrc
```

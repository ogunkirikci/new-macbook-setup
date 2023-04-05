
# New Macbook Setup

## Browser
- Chrome
https://www.google.com/chrome/
- Brave
https://brave.com/download/
- Why Brave?
https://medium.com/@i_m_vampire_/why-developers-should-switch-to-brave-browser-8b111b520adc

## Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Brew Services
```bash
brew install tree wget vim fig git htop imagemagick ffmpeg tmux
```
```bash
brew install --cask iterm2 visual-studio-code
````

## Install iTerm2
```bash
https://iterm2.com/downloads.html
```
## Install ohmyzsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install powerlevel10k
1. Clone the repository
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
2. Set ```ZSH_THEME="powerlevel10k/powerlevel10k"``` in ```~/.zshrc```.

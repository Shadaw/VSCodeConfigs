# Extenções vscode

### listar comandos vscode (unix)
```bash
code --list-extensions | xargs -L 1 echo code --install-extension
```

### listar comandos vscode (windows)
```bash
code --list-extensions | % { "code --install-extension $_" }
```

### output
```bash
code --install-extension ahmadawais.shades-of-purple
code --install-extension ban.spellright
code --install-extension dbaeumer.vscode-eslint
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension jolaleye.horizon-theme-vscode
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension lkytal.pomodoro
code --install-extension mischah.relaxed-theme
code --install-extension ms-vscode-remote.remote-wsl
code --install-extension naumovs.color-highlight
code --install-extension PKief.material-icon-theme
code --install-extension WakaTime.vscode-wakatime
```
# Nicer Terminal
Make your mac terminal prompt (.zshrc) a bit nicer.

### Änderungen Terminal Prompt
```zsh
PROMPT='%F{89}path: %~%f'   # "path: " gefolgt vom aktuellen Pfad in der ersten Zeile
PROMPT+='
'   # Erzeugt eine neue Zeile nach dem Pfad
PROMPT+='%F{75}%n@%m%f %# '  # Benutzername und Hostname in der zweiten Zeile
```

### Alias für ls mit Farben
```zsh
alias ls='ls -l -a -G -p'
```
or
```zsh
alias ls='ls -a -G -p'
```

### LS_COLORS für die Farbkonfiguration
```zsh
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
```

# sam-zsh-completion

## How to use

`~/.zshrc`

```
autoload -U +X bashcompinit && bashcompinit
autoload -Uz compinit
compinit -u

autoload -U ~/.zsh/complete/*
```

Add `_sam` at `~/.zsh/complete/`

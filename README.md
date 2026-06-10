dotfiles that I may or may not have borrowed from somewhere else...

## Files

- `.zshrc` - Oh My Zsh setup with a simple Gruvbox-friendly prompt.
- `.tmux.conf` - tmux setup with Gruvbox TPM theme, centered tabs, and hostname on the right.
- `zsh/themes/gruvbox-simple.zsh-theme` - simple `path >` prompt theme.
- `iterm/gruvbox-dark.itermcolors` - Gruvbox Dark iTerm color preset.
- `vscode/` - VS Code settings and keybindings.

## Local Secrets

Do not commit secrets to this repo. Put machine-local exports in:

```zsh
$HOME/.config/zsh/secrets.zsh
```

The `.zshrc` sources that file only when it exists.

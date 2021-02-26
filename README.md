# rails-aliases

Consult [source file](rails-aliases.plugin.zsh) for more details.


## Installation

### [zinit](https://github.com/zdharma/zinit)

```zsh
zinit load samflores/rails-aliases
# or
zinit light samflores/rails-aliases
```

### [zplug](https://github.com/zplug/zplug)

```zsh
zplug "samflores/rails-aliases", use:rails-aliases.plugin.zsh
```

### [Antigen](https://github.com/zsh-users/antigen)

```zsh
antigen bundle samflores/rails-aliases.git
```

### Manual

Download the latest released `rails-aliases.plugin.zsh` to `$ZSH/plugins/rails-aliases`: 
```shell
curl --create-dirs -o $ZSH/plugins/rails-aliases/rails-aliases.plugin.zsh -sL \
$(curl -s https://api.github.com/repos/samflores/rails-aliases/releases \
| grep browser_download_url \
| head -n 1 \
| cut -d '"' -f 4)
```

Add `rails-aliases` to `plugins` in `$ZDOTDIR/.zshrc`.

Restart the shell.


## Note

No actions are `-f`orced by default: This is at user's discretion. 

# my_shell
Settings of my personal shell

## Terminal
- MacOS: [iTerm](https://iterm2.com/downloads.html)
- Windows: [Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701)

## Install Fonts
- [FiraCode](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/FiraCode.zip)

## Install Nushell

```bash
# * You might need to update rust
rustup update

# Installation with Cargo
cargo install nu
```

## Starship


```bash
# Install it with cargo 
cargo install starship --locked

# Setup 
mkdir ~/.cache/starship
starship init nu | save -f ~/.cache/starship/init.nu

# Add it to nushell
echo "source ~/.cache/starship/init.nu" | save --append $nu.config-path

 ~/.config/starship.toml
```

## Install Neovim

```bash
# MacOS
brew install neovim
```

Set it up [AstroNvim conf](https://github.com/Xoffio/xo_astro_conf)

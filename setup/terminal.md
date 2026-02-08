# Terminal setup (Alacritty and shell)

- Install a [Nerd Font](https://www.nerdfonts.com/font-downloads) (JetBrainsMono)
  - Windows: select all &rarr; right click &rarr; Install
  - Linux: move folder to `~/.local/share/fonts`
- Set up shell
  - Windows:
    - Install PowerShell (not the pre-installed Windows PowerShell)
    - Clone PowerShell repo into Documents
  - Linux:
    - Clone bash repo into `~/.config`
    - From home directory, run:
      - `rm .bashrc`
      - `ln -s .config/bash/.bashrc .bashrc`
- Install Alacritty
- Clone alacritty repo into `$env:appdata` on Windows / `~/.config` on Linux

# Terminal setup (Alacritty and shell)

- Install a [Nerd Font](https://www.nerdfonts.com/font-downloads) (JetBrainsMono)
  - Windows: select all &rarr; right click &rarr; Install
  - Linux: move folder to `~/.local/share/fonts`
- Set up shell
  - Windows:
    - Install PowerShell (not the pre-installed Windows PowerShell)
    - Clone [PowerShell repo](https://github.com/Andrew-v-C/PowerShell) into Documents
  - Linux:
    - Clone [bash repo](https://github.com/Andrew-v-C/bash) into `~/.config`
    - From home directory, run:
      - `rm .bashrc`
      - `ln -s .config/bash/.bashrc .bashrc`
- *If using a headless Linux setup (e.g. Raspberry Pi), skip the following steps*
- Install Alacritty
- Clone [alacritty repo](https://github.com/Andrew-v-C/alacritty) into `$env:appdata` on Windows / `~/.config` on Linux

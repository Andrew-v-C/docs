# Terminal setup (Alacritty and shell)

- Set up shell
  - Windows:
    - Install PowerShell (not the pre-installed Windows PowerShell)
    - Clone [PowerShell repo](https://github.com/Andrew-v-C/PowerShell) into Documents
  - Linux:
    - Clone [shell repo](https://github.com/Andrew-v-C/shell) into `~/.config`
    - From home directory, run:
      - `rm .profile .bashrc`
      - `ln -s .config/shell/.profile .profile`
      - `ln -s .config/shell/.bashrc .bashrc`
- *If using a headless Linux setup (e.g. Raspberry Pi), skip the following steps*
- Install a [Nerd Font](https://www.nerdfonts.com/font-downloads) (JetBrainsMono)
  - Windows: select all &rarr; right click &rarr; Install
  - Linux: move folder to `~/.local/share/fonts`
- Install Alacritty
- Clone [alacritty repo](https://github.com/Andrew-v-C/alacritty) into `$env:appdata` on Windows / `~/.config` on Linux

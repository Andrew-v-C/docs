# Linux computer setup

## To start
- Update/upgrade packages
- If using desktop, install Google Chrome (for easy referencing of docs)
  - Get .deb from official site
- Set up Git
  - Install Git
  - Create `~/.gitconfig` with the following lines:
    ```
    [user]
        name = <username>
        email = <email>
    ```

## Set up terminal/shell
- If using desktop:
  - Install a [Nerd Font](https://www.nerdfonts.com/font-downloads) (JetBrainsMono)
    - Download and place folder in `/usr/local/share/fonts`
  - Install Alacritty
  - Clone [alacritty repo](https://github.com/Andrew-v-C/alacritty) into `~/.config`
- Clone [shell repo](https://github.com/Andrew-v-C/shell) into `~/.config`
- From home directory, run:
  - `rm .profile .bashrc`
  - `ln -s .config/shell/profile.sh .profile`
  - `ln -s .config/shell/bashrc.sh .bashrc`

## Install misc. packages
- curl
- npm
- tree-sitter-cli (via npm): `sudo npm install -g tree-sitter-cli`

## Python tools
- Python should be installed
- Install:
  - python-is-python3
  - pip
  - pipx
  - Pyright (via npm): `sudo npm install -g pyright`
  - Ruff (via pipx): `sudo pipx install --global ruff`

## C/C++ tools
- Install:
  - CMake
  - clang
  - clangd
  - clang-format
  - Ninja build system
  - Conan (via pipx): `sudo pipx install --global conan`

## Install lua-language-server (for editing Neovim configs)
- Download tarball from [latest release](https://github.com/LuaLS/lua-language-server/releases/latest)
- Extract to `/opt/lua-language-server`
- Create wrapper script (`lua-language-server`) in `/usr/local/bin`
- For reference: formatting options can be found [here](https://github.com/CppCXY/EmmyLuaCodeStyle/blob/master/docs/format_config_EN.md)

## TOML tools
- Install Taplo (via npm): `sudo npm install -g @taplo/cli`

## Install Neovim
- Download tarball from [latest release](https://github.com/neovim/neovim/releases/latest)
- Extract to `/opt/neovim`
- Create wrapper script (`nvim`) in `/usr/local/bin`
- Clone [nvim repo](https://github.com/Andrew-v-C/nvim) into `~/.config`

## LaTeX tools (Tectonic)
- Download executable form [latest release](https://github.com/tectonic-typesetting/tectonic/releases/latest)
- Place in `/usr/local/bin`

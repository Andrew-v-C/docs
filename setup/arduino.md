## Arduino tools
- Install Arduino CLI
  - Windows: use winget
  - Linux: get .deb from [latest release](https://github.com/arduino/arduino-cli/releases/latest)
- Install arduino-language-server
  - Download executable from [latest release](https://github.com/arduino/arduino-language-server/releases/latest)
  - Place in folder in Path
    - `usr/local/bin` on Linux
### Considerations
- On Linux: likely need to add users to certain group in order to access ports:
  - Run `sudo usermod -aG dialout <user>`
  - Log out/in of user account for change to take effect
  - Type `groups` when logged in as user; confirm `dialout` is there
- Users must create a config file: `arduino-cli config init`
- When creating a new sketch, create `sketch.yaml` with the following lines:
  ```
  default_fqbn: <FQBN>
  default_port: <Port>
  ```

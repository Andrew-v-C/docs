# General setup for all computers

- Install Google Chrome (for easy referencing of setup docs)
  - *Skip this if using a headless setup*
  - Windows: use winget
  - Linux: install .deb from official website
- Create folders in home folder
  - `Projects`
  - Software folder (named `Software` on Windows / `.Software` on Linux)
  - `.local/bin`
    - On Windows: add folder to Path environment variable
- Set up Git
  - Install Git
  - Create `.gitconfig` file in home folder with the following lines:
    ```
    [user]
        name = <username>
        email = <email>
    ```
- Set up [terminal](https://github.com/Andrew-v-C/docs/blob/main/setup/terminal.md)
- Set up [editor](https://github.com/Andrew-v-C/docs/blob/main/setup/editor.md)

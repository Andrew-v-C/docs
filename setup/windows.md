# New Windows computer setup

- Refer first to [general setup](https://github.com/Andrew-v-C/docs/blob/main/setup/general.md)


## In browser
- Sign into accounts
- Download wallpaper &rarr; right click &rarr; Set as desktop background


## File explorer
- Keep only the following pinned to Quick access:
  - Home folder
  - Documents
  - Downloads
  - Pictures
  - Projects
- Options &rarr; General &rarr; uncheck all "show" options
- View &rarr; Show &rarr; file name extensions and hidden items


## Settings app

### System
- Display &rarr; enable Night light
- Sound &rarr; More sound settings &rarr; Sounds &rarr; "No sounds"
- Power & battery &rarr; show percentage; never turn off screen or put device to sleep
- Storage &rarr; turn on Storage Sense

### Bluetooth & devices
- Mouse &rarr; turn off "Enhance pointer precision"
- Keyboard &rarr; set repeat delay and repeat rate to shortest / fastest possible

### Personalization
- Colors &rarr; dark mode; transparency effects on; automatic accent color
- Themes &rarr; Desktop icon settings &rarr; uncheck all icons
- Lock screen &rarr; Lock screen status "None"
- Start &rarr; "More pins"; turn off all "show" options
- Taskbar &rarr; hide Search; turn off Task view and Widgets
- Multitasking &rarr; turn off Snap windows; don't show tabs when pressing Alt+Tab

### Time & language
- Date & time
- Language & region

### Accessibility
- Keyboard &rarr; Sticky keys &rarr; turn off keyboard shortcut


## Customize keyboard mappings/shortcuts
- Install SharpKeys
  - Remap Caps Lock to Control
  - Disable Num Lock

### Set up terminal shortcut
- Ensure Alacritty menu shortcut starts in `%USERPROFILE%`
- Install PowerToys
- Create a .bat file containing `start alacritty`; save in a Scripts folder in Software
- Use PowerToys Keyboard Manager to map `Win + T` to run the script, starting in `%USERPROFILE%`
- Turn off all other PowerToys utilities


## Cleanup
- Uninstall unnecessary apps
- Delete all desktop shortcuts
- Unpin all apps from taskbar
- Keep only useful apps pinned to Start


## Useful apps to install
- Discord
- Google Drive
- KiCad
- LTspice
- LibreOffice
- Okular
- Raspberry Pi Imager


## Optional tweaks
- Adjust keyboard repeat delay/rate in registry
- Remove "Recommended" from Start

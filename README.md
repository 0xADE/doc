# Another Desktop Environment

Basic principles:
- oriented to skilled Linux users who understand how the system works
- minimize distractions
  - no large panels/launchers with a lot of useless info
  - minimize number of modal actions
  - fast finding and filtering of objects instead of hierarchical menus
- tile management for applications

Based on:
- Wayland
- sway
- custom apps

The project is the playground for my ideas about UI and testing
solutions based on different languages and frameworks. In the first
approach I try to made apps with Go + Fyne. For convenience short apps
could made with C/Nim. Maybe later it could be revised. The way is
misty.

## Parts of solution

All backend applications of ADE use `ade-` as name prefix. Names of UI
apps may vary.

- [ADE Login & Desktop Manager](ade-ldm/README.md)
- [ADE Files Metadata Indexer](ade-metad/README.md)

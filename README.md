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

Apps in the first approach made with Go + Fyne. Later it could be
revised. For convenience short apps could made with C.

## Parts of solution

All backend applications of ADE use `ade-` as name prefix. Names of UI
apps may vary.

- [ADE Login & Desktop Manager](ade-ldm/README.md)
- [ADE Files Metadata Indexer](ade-metad/README.md)

# Shortcuts

This repository contains various shortcuts and scripts.

## kbs

`kbs` is a Python script that helps manage application launch shortcuts within Karabiner-Elements. It specifically works with shortcuts configured under the "Hyper Key base layer (Tab held down alone)" rule.

### Usage:

- **Add a shortcut:**
  `./kbs add <key_code> <app_name>`
  Example: `./kbs add h Ghostty` (This would open the 'Ghostty' application when Hyper + H is pressed.)

- **List all shortcuts:**
  `./kbs list`

- **Remove a shortcut:**
  `./kbs remove <identifier>`
  The identifier can be the shortcut's description (e.g., "Open Ghostty") or the key code (e.g., "h").

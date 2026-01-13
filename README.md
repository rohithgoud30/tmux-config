# Tmux Config

My personal tmux configuration for macOS.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/rohithgoud30/tmux-config.git ~/tmux-config
   ```

2. Create a symlink to use this config:

   ```bash
   ln -s ~/tmux-config/tmux.conf ~/.tmux.conf
   ```

   Or simply copy the file:

   ```bash
   cp ~/tmux-config/tmux.conf ~/.tmux.conf
   ```

3. Reload tmux (if already running):
   ```
   Ctrl+a then r
   ```

## Features

- **Prefix key**: `Ctrl+a` (instead of default `Ctrl+b`)
- **Mouse support**: Enabled for easy pane selection and resizing
- **256-color support**: Full color terminal
- **Custom theme**: Blue/cyan color scheme with status bar
- **Pane navigation**: Fn + Arrow keys for intuitive pane movement
- **Window reordering**: Ctrl + Shift + Arrow keys
- **Synchronize panes**: Toggle with `Ctrl+a y`
- **Easy config reload**: `Ctrl+a r`

## Key Bindings

See [CHEATSHEET.md](CHEATSHEET.md) for a complete reference of all key bindings and CLI commands.

## Requirements

- macOS (uses Fn + Arrow keys which map to Home/End/PageUp/PageDown)
- tmux 3.0+

## Status Bar

The status bar shows:

- Hostname with computer emoji
- Current session name
- Current time

Custom colors:

- Active window: Bold blue background
- Inactive windows: Cyan/green foreground
- Active pane border: Bright cyan
- Inactive pane border: Cyan

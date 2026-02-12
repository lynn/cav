# cav

**cav** is a Bash script for managing Balatro mods. :banana: :zap: :sparkles:

**Currently it only works on Linux.**

1. Install Balatro through Steam on Linux
2. Run `curl https://raw.githubusercontent.com/lynn/cav/refs/heads/main/cav > ~/.local/bin/cav`
3. Run `cav install` to install Lovely and Steamodded
4. Run `cav new` to start making a new mod!
5. (WIP) Run `cav mods` to list available mods, and `cav add <xyz>` to install a mod.

## Commands

| Command | Description |
| ------- | ----------- |
| `cav install` | Install [Lovely](https://github.com/ethangreen-dev/lovely-injector) and [Steamodded](https://github.com/Steamodded/smods). |
| `cav install lovely` | Force-reinstall the latest version of Lovely. |
| `cav install steamodded` | Force-reinstall the latest version of Steamodded. |
| `cav list lovely` | List available versions of Lovely. |
| `cav list steamodded` | List available versions of Steamodded. |
| `cav status` | View installed versions of Lovely and Steamodded. |
| `cav uninstall` | Uninstall Lovely and Steamodded. |
| `cav new` | Create a new mod in the `Mods` folder. |
| `cav mods` | List mods available for installation. |
| `cav add <mod>` | Install a mod. |



# A simple bash script for a power menu (sleep, shutdown, reboot, lock, logout)

## Dependencies

- fzf

## Setup

Make the script executable:

```bash
chmod +x ~/superior-mango-dotfiles/scripts/powermenu.sh
```

## Usage with MangoWM

Add a keybind and a window rule to your Mango config. Don't forget to change the path of the script in the keybind.

**Keybind:**

```
bind=SUPER+SHIFT,e,spawn_shell,foot --title="Floating-Powermenu" -e ~/superior-mango-dotfiles/scripts/powermenu.sh
```

**Window rule:**

```
window_rule=title:Floating-Powermenu,width:300,height:250,is_floating:1
```

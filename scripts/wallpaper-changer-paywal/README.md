# A simple bash script for changing wallpaper with pywal to generate a color palette

## Dependencies

- awww
- fzf
- pywal

## Setup

Make sure your wallpapers are in `~/Pictures/Wallpapers/`.

Make the script executable:

```bash
chmod +x ~/superior-dotfiles-mango/scripts/wallpaper.sh
```

## Usage with MangoWM

Add a keybind and a window rule to your Mango config. Don't forget to change the path of the script in the keybind :p

**Keybind:**

```
bind=SUPER,w,spawn_shell,kitty --title="Floating-Wallpaper" -e ~/superior-dotfiles-mango/scripts/wallpaper.sh
```

**Window rule:**

```
windowrule=title:Floating-Wallpaper,width:700,height:500,isfloating:1
```

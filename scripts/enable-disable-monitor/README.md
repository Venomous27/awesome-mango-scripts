# A simple bash script for enabling/disabling monitors in multi-monitor setups

In `monitor.sh`, change the monitor names to match your monitors.

Use `wlr-randr` to get your monitor's name, make, model, and serial.

You can also add more options according to your needs.

## Setup

Make the script executable:

```bash
chmod +x ~/superior-dotfiles-mango/scripts/monitor.sh
```

## Usage with MangoWM

Add a keybind and a window rule to your Mango config. Don't forget to change the path of the script in the keybind :p

**Keybind:**

```
bind=SUPER,p,spawn_shell,kitty --title="Floating-Monitor" -e ~/superior-dotfiles-mango/scripts/monitor.sh
```

**Window rule:**

```
windowrule=title:Floating-Monitor,width:300,height:200,isfloating:1
```

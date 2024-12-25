# waybar pimp-module

[PimpMyRice](https://github.com/daddodev/pimpmyrice) module for [Waybar](https://github.com/Alexays/Waybar).

## Set up

```bash
pimp clone module pimp://waybar
```

add to `~/.config/waybar/config`:

```json
    "reload_style_on_change": true,
```

add to your base-style:

```json
{
    ...
    "modules_styles": {
        "waybar": {
            "variant": "split", # or "solid"
            "colorful": "no" # or "background" or "foreground"
        }
    }
}
```

# My Alacritty Configuration

This is my personal alacritty configuration.

Setup:

1. On your local machine navigate to `~/.config/`. Before running this command make sure that the `alacritty` directory has not already been created. Otherwise you can pick choose config values you want by inspecting [alacritty.toml](https://github.com/Audiosutras/My-Alacritty-Toml-Config/blob/main/alacritty.toml)

```bash
git clone https://github.com/Audiosutras/My-Alacritty-Toml-Config.git alacritty
```

Comment out (`#`) the `[fonts]` section in `alacritty.toml` until you download [nerd fonts](https://www.nerdfonts.com/) or clone the **Patched Fonts** repository [here](https://github.com/Audiosutras/Patched-Fonts).

Alacritty [themes](https://github.com/alacritty/alacritty-theme) are included in this repository.
 To add a theme add the following to the top of
 `alacritty.toml` where `{theme}` is the name of
 the theme that should be imported.

```.toml
import = [
  "~/.config/alacritty/themes/themes/{theme}.toml"
]
```
```

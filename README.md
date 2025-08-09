# Ventoy-Flat-Catppuccin
A flat Catppuccin Mocha (Blue) theme for Ventoy.

## Installation

> [!IMPORTANT]
> This theme is intended to be displayed at the resolution `1280x720` or higher.
> Displaying it at lower resolutions will result in elements getting cut-off.

1. Clone the repo: `git clone https://github.com/KindaSuS1368/Ventoy-Flat-Catppuccin`
2. Paste the `theme-vfc` folder into the `/ventoy/themes/` folder inside your Ventoy drive.
3. Modify the `/ventoy/ventoy.json` file to contain
```json
{
    "theme":{
        "file":[
            "/ventoy/themes/theme-vfc/theme.txt"
        ],
        "fonts":[
            "/ventoy/themes/568flat_x2/ComicMono.pf2",
        ]
    }
}
```

## Credits

- This theme is based on the awesome [568flat-ventoy-theme](https://github.com/PJ-568/568flat-ventoy-theme) by [PJ-568](https://github.com/PJ-568).
- The font used in this theme is [Comic Mono](https://dtinth.github.io/comic-mono-font/) compiled into a GRUB .pf2 font file with font size 24. additionaly, the `max-height` value of the font was increased from 25 to 32 to mitigate rendering issues.
- **Disclaimer:** The [wallpaper](/theme-vfc/background.jpg) included in this theme is not my original work.
Its source and license are unknown. If you are the copyright holder and would like it removed, please open an issue or submit a pull request.

# Ventoy Flat Catppuccin

A flat Catppuccin Mocha (Blue) theme for Ventoy.

![Preview](/assets/Preview.png)


## Installation

> [!IMPORTANT]
> This theme is intended to be displayed at the resolution `1280x720` or higher. Displaying it at lower resolutions will result in elements getting cut-off.
> 
> Only the languages that are written in the Roman script, without accents, are supported.

> [!NOTE]
> Elements may appear small on high DPI displays.
>
> The mode indicators in the status (bottom) bar (Memdisk, UEFI FS, etc) only show when you enable the respective mode. You can get details about enabling these modes by pressing `F1` in Ventoy.

1. Download the `theme-vfc.zip` from the latest [GitHub release](https://github.com/KindaSuS1368/Ventoy-Flat-Catppuccin/releases/latest), extract it.
2. Paste the extracted `theme-vfc` folder into the `/ventoy/themes/` folder inside your Ventoy drive.
3. Modify the `/ventoy/ventoy.json` file to contain

```json
{
    "theme":{
        "file": "/ventoy/themes/theme-vfc/theme.txt",
        "fonts": "/ventoy/themes/theme-vfc/ComicMono.pf2",
        "gfxmode": "max"
    }
}
```


## Credits

- This theme is based on the awesome [568flat-ventoy-theme](https://github.com/PJ-568/568flat-ventoy-theme) by [PJ-568](https://github.com/PJ-568).
- The font used in this theme is [Comic Mono](https://dtinth.github.io/comic-mono-font/) compiled into a GRUB .pf2 font file with font size 24. Additionally, the `max-height` value of the font was increased from 25 to 32 to mitigate rendering issues.
- The color palette used is [catppuccin](https://catppuccin.com/).


## Licenses

The files under [/theme-vfc](/theme-vfc) are licensed under this MIT License: [/LICENSE-Theme](/LICENSE-Theme) with three exceptions.
1. [/theme-vfc/ComicMono.pf2](/theme-vfc/ComicMono.pf2) is licensed under this MIT License: [/LICENSE-ComicMono](/LICENSE-ComicMono)
2. The catppuccin color pallette is licensed MIT under this license: [/LICENSE-Catppuccin](/LICENSE-Catppuccin)
3. [The wallpaper](/theme-vfc/background.jpg) included in this theme is not my original work.
Its source and license are unknown. If you are the copyright holder and would like it removed, please open an issue or submit a pull request.

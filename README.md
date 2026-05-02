# base24_colortool <img alt="Color wheel" src="https://raw.githubusercontent.com/tinted-theming/home/refs/heads/main/color_wheel.png" width="100" align="right" style="padding-top:0.6rem;">

[Base24] template / themes for use with CMD.exe colortool / Color Tool April 2019 from https://github.com/microsoft/terminal/releases/tag/1904.29002 built using [Tinted Theming color schemes].

If you are using Microsoft Terminal, see https://github.com/tinted-theming/tinted-terminal/ for color themes.

## Previews

TODO screenshots.

## Installation

Assuming an already configured and working ColorTool.exe:

 1. Locate ColorTool.exe, there will be a `schemes` directory in the same directory as the exe
 2. Copy theme(s) from `themes/base24` into `schemes`
 3. Issue:

        ColorTool.exe -s                    # to list
        ColorTool.exe base24-dracula.ini    # to use Dracula theme, NOTE .ini extension is required


## Building

This repo auto builds with new color schemes as they are added to
https://github.com/tinted-theming/schemes or when this repo is updated.

You can also build locally using **any** (base24) builder you like.
https://github.com/tinted-theming/tinted-builder-rust/releases provides
pre-built binaries for most platforms and can build both base16 and base24
some notes and tips are below.

    # checkout colors and this theme template
    git clone https://github.com/tinted-theming/schemes.git
    git clone https://github.com/clach04/base24_colortool.git

    # build (assuming tinted-builder-rust is in path)
    tinted-builder-rust build --schemes-dir schemes\base24 base24_colortool

Base24 schemes are recommended rather than Base16, due to Windows Terminals/CMD supporting 16 colors.

## Team

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/clach04/base24_colortool/graphs/contributors).

| [![clach04](https://github.com/clach04.png?size=100)](https://github.com/clach04) |
| --------------------------------------------------------------------------------- |
| [clach04](https://github.com/clach04)                                             |

## Community

  * [Tinted Theming Home](https://github.com/tinted-theming/home)
  * Have something you want to discuss, but you're not sure it warrants an issue? Feel free to stop by
    [#tinted-theming:matrix.org](https://matrix.to/#/#tinted-theming:matrix.org) on [Matrix](https://matrix.org/).

## License

[MIT License](./LICENSE)


[Base24]: https://github.com/tinted-theming/home/blob/main/styling.md
[Tinted Theming color schemes]: https://github.com/tinted-theming/schemes

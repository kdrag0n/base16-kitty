# base16-kitty
[Base16](https://github.com/chriskempson/base16) for the [kitty](https://github.com/kovidgoyal/kitty) terminal emulator

# Installation
Simply copy the contents of your desired color scheme into your `kitty.conf` file. If you already have a color scheme in your configuration, be sure to remove or comment it out.

`kitty.conf` location:
 - Linux: `~/.config/kitty/kitty.conf`
 - macOS: `~/Library/Preferences/kitty/kitty.conf`

# `256` Variants
The 256 variants are for those who wish to continue using the 16 ANSI colors but don't want to end up with weird-looking colors instead of bright ones. Because base16 schemes are only 16-color, all of the bright colors mirror their non-bright variants instead of being unique colors. If you use the 256 variants, you will also need to use [base16-shell](https://github.com/chriskempson/base16-shell) to maintain proper compatibility with the base16 themes.

### TL;DR if some colors look weird, darker than normal, or incorrect, try a `256` variant.
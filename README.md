# dmenu

This is just a standard dmenu, but with fonts and colors set to match my color scheme.

## Emoji enabled

If you want to use emojis and color fonts, install `libxft-bgra-git` from AUR.
There is currently bug in libxft that prevents color fonts to function properly in suckless software.
This dmenu fork is already patched.
If you want to patch you own dmenu, search for *color fonts* in drw.c and remove block of code underneath (line 138-149), and of course install `libxft-bgra-git`.

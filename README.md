xmodmap
===

These are X11 keyboard mapping files for HHKB (and some other models of keyboards).

`0-9` and `!@#$%^&*()` are swapped in the "prog" version.

usage
---

`unix> xmodmap ./.Xmodmap`

`unix> xmodmap ./.Xmodmap_prog`

more...
---

It would be more convenient if you change some keyboard shortcuts.

For example:

    Ctrl + Alt + A -> xmodmap ~/.Xmodmap
    Ctrl + Alt + S -> xmodmap ~/.Xmodmap_prog
    Alt + 4 -> Alt + F4
    ...

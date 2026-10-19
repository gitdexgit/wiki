`xsetroot` is a built-in X11 tool that colors your desktop background without needing extra wallpaper apps.

Run this in your terminal to turn your screen pitch black right now:
```bash
xsetroot -solid "#000000"
```

To keep it black every time i3 starts, remove any `feh` (optional) lines in `~/.config/i3/config` if you have any (option). Simply add this:
```text
exec_always --no-startup-id xsetroot -solid "#000000"
```

Now you don't need to write it manually every single time. But write it manually why not?

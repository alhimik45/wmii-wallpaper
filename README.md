Switchable wallpapers (by timeout or shortcut) for wmii. 
Application is controlled by named pipe.

Usage example:

```bash
node wmii-wallpaper.js  /path/to/images  /path/to/named/pipe switch_timeout(in minutes)
```

Write something to pipe to initiate wallpaper switching:

```bash
echo next > $WALLPAPER_FIFO_IN
```

Copyright © 2015 Alexey Kolpakov

Distributed under DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE.

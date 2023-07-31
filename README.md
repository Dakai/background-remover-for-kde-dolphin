# background-remover-for-kde-dolphin

A right click menu entry to use rembg to remove image's background in Kde Dolphin file manager

## Demo

https://github.com/Dakai/background-remover-for-kde-dolphin/assets/1525214/e4fed8ad-78de-422f-bddc-db255d39c037

## Install

First install `rembg[cli]` from https://github.com/danielgatis/rembg

Make the script file executable and move it to `~/.local/bin` or `/usr/local/bin`.

```
chmod +x ./rembg_script.sh
cp ./rembg_script.sh /usr/local/bin/rembg_script.sh
```

Move the desktop file to `~/.local/share/kservices5/ServiceMenus/`

```
mv ./rembg.desktop ~/.local/share/kservices5/ServiceMenus/
```

Login and logout to see the changes

## Credits

This Project make use of [Rembg](https://github.com/danielgatis/rembg) for the awesome AI background remover,<br/>
and inspired by the [Background-remover-for-nemo](https://github.com/supersuryaansh/background-remover-for-nemo) project.

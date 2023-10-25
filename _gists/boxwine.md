---
name:  "boxwine"
description: Installs .exe file to it's own wine prefix.
requirements: jq, tar, wine, winetricks, zenity
download: https://gist.githubusercontent.com/xerocuil/2e06df4e4919e7a4845321d8b63ec6c1/raw/boxwine.sh
source: https://gist.github.com/xerocuil/2e06df4e4919e7a4845321d8b63ec6c1
updated: 2022-06-14
---

**Usage**

`boxwine <path_to_exe>`

**Note**

Boxwine will look for a `docs` directory in the path that contains the installer file, if an `icon.png` file is present, this will be used as the icon for the desktop configuration file that will be created for the start menu.

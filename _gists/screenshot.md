---
name:  "screenshot"
description: Take screenshot of current window and save to folder (for XFCE).
requirements: xfce4-screenshooter
download: https://gist.githubusercontent.com/xerocuil/05516a42793752c6cd3ef20e0eb477b0/raw/screenshot.sh
source: https://gist.github.com/xerocuil/05516a42793752c6cd3ef20e0eb477b0
updated: 2023-10-24
---

**Usage**

`screenshot <option>`

Options			  | Description
:------			  | :----------
`fullscreen`	| Take screenshot of entire screen
`region`		  | Take screenshot of selected region
`window`		  | Take screenshot of selected window

If no option is given, `window` will be the default option. Screenshots will be saved to `$HOME/Screenshots`.
